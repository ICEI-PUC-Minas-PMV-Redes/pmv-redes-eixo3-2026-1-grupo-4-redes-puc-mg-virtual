# Código do Servidor (Back-end)

const dias = ['domingo','segunda-feira','terça-feira','quarta-feira','quinta-feira','sextafeira','sábado'];
const hoje = dias[new Date().getDay()];
return items
 .filter(item => {
 const ativo = String(item.json.ATIVO || 'SIM').toUpperCase() === 'SIM';
 const dia = String(item.json.DIA_SEMANA || '').toLowerCase().trim();
 return ativo && dia === hoje;
 })
 .map(item => ({
 json: {
 ...item.json,
 deveEnviar: true,
 assunto: item.json.ASSUNTO,
 mensagem: item.json.MENSAGEM_HTML,
 destinatario: item.json.DESTINATARIO || 'destinatario@empresa.com'
 }
 })
## Organização

Organize os arquivos conforme o tipo de solução desenvolvida:

### Shell Scripts

Se a solução utiliza shell scripts, organize-os aqui com nomes descritivos:

```cmd
servidor/
├── scripts/
│   ├── configurar-firewall.sh
│   ├── monitorar-rede.sh
│   └── backup-configuracao.sh
└── README.md
```

### Back-end .NET / Outra Tecnologia

Se a solução utiliza uma API ou serviço back-end, organize conforme a estrutura padrão da tecnologia:

```cmd
servidor/
├── src/
│   └── (código-fonte)
├── tests/
│   └── (testes)
└── README.md
```

## Como Executar

*(Descreva aqui como executar o servidor localmente para desenvolvimento e testes.)*

## Variáveis de Ambiente

*(Liste as variáveis de ambiente necessárias, sem incluir valores reais de produção.)*

| Variável | Descrição | Exemplo |
|----------|-----------|---------|
| *(Variável)* | *(Descrição)* | *(Exemplo)* |
