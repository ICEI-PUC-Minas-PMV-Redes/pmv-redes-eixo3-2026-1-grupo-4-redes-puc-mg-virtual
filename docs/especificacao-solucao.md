# Especificação da Solução

## 1. Parceiro / Comunidade

### 1.1 Identificação

| Campo | Descrição |
|-------|-----------|
| **Nome da comunidade/organização** | *Armarinhos Tavares* |
| **Tipo de organização** | *EMPRESA* |
| **CNPJ (se aplicável)** | *29.490.761/0001-50* |
| **Endereço completo** | Rua Claudinei de Oliveira Silva, 166 Francisco Morato São Paulo - SP|
| **Bairro / Cidade / UF** | *Jardim Vassouras. Francisco Morato. SP* |
| **Responsável pelo contato** | *Adriana - Gerente* |
| **E-mail** | *armarinhotavares@gmail.com* |
| **Telefone** | *11 94500-6561* |
| **Data do primeiro contato** | *24/02/2025*|

### 1.2 Contexto da Comunidade

*A comunidade parceira escolhida é a Tavares Armarinhos, uma loja de pequeno porte que atende a população local com produtos de armarinho e itens diversos.
A loja possui 1 funcionário, 1 gerente e 1 proprietário, totalizando 3 pessoas na operação, com média de 30 atendimentos por dia. Sua estrutura de tecnologia é básica, voltada para atendimento, comunicação, controle de vendas e organização interna.
Os principais desafios na área de TI e redes são melhorar a estabilidade da internet, proteger os dados da loja, organizar os equipamentos, realizar backups e tornar os processos mais seguros.
Também será proposta uma política básica de cibersegurança, com boas práticas como uso de senhas fortes, não compartilhamento de acessos, cuidado com links suspeitos, atualização dos equipamentos, backup de dados e proteção da rede Wi-Fi.*

### 1.3 Termo de Parceria

*(Indique se o termo de parceria foi assinado e onde está arquivado. O documento escaneado/fotografado deve ser incluído na pasta `evidencias/termos/`.)*

- [ ] Termo de parceria assinado e arquivado em `evidencias/termos/`

---

## 2. Problema Identificado

*Este projeto propõe a implementação de uma política de cibersegurança em uma loja que atualmente opera com infraestrutura básica, utilizando conexão residencial e sem diretrizes formais de segurança digital. A análise inicial identificou vulnerabilidades relevantes, como ausência de controle de acesso, falta de rotinas de backup e inexistência de mecanismos adequados de proteção contra ameaças. Diante disso, a proposta consiste na adoção de medidas práticas e acessíveis, incluindo padronização de boas práticas de uso, fortalecimento da gestão de senhas, implementação de soluções de proteção (como antivírus e atualizações regulares), estruturação de rotinas de backup e melhorias na configuração da rede. O objetivo é reduzir riscos operacionais, proteger os dados da empresa e garantir maior estabilidade e segurança nas atividades diárias.*

---

## 3. Solução Proposta

### 3.1 Descrição Geral

*A solução proposta consiste na implementação de uma política básica de cibersegurança na loja, com foco em ações práticas e de baixo custo. Será realizada a atualização contínua do sistema operacional e aplicativos, instalação e manutenção de antivírus ativo, além da adoção de boas práticas de navegação para evitar ameaças como malware e phishing. Também será implantada uma gestão adequada de senhas, com uso de credenciais fortes e, quando possível, autenticação em dois fatores.
Para garantir a segurança dos dados, serão definidos procedimentos de backup periódico em mídia externa ou nuvem. No aspecto físico, será configurado o bloqueio automático do computador e restrição de acesso a usuários autorizados. Por fim, a rede Wi-Fi será protegida com senha forte, criptografia WPA2/WPA3 e alteração das credenciais padrão do roteador. Essas ações visam reduzir vulnerabilidades e aumentar a segurança e confiabilidade do ambiente.*

### 3.2 Objetivos

**Objetivo geral:**

*Implementar uma política básica de cibersegurança na loja Tavares Armarinhos, visando reduzir vulnerabilidades, proteger dados sensíveis e garantir maior estabilidade, segurança e confiabilidade nas operações diárias, por meio de ações práticas e de baixo custo, como gestão de senhas, backups periódicos, proteção da rede Wi-Fi e adoção de boas práticas de navegação.*

**Objetivos específicos:**

1. *Realização de Backup*
2. *Implementação de Políticas de Segurança*
3. *Gestão de Senhas*
4. *Adoção de boas práticas de Navegação*

### 3.3 Escopo da Solução

* Implementação de política básica de cibersegurança com boas práticas (senhas fortes, não compartilhamento de acessos, cuidado com links suspeitos)
· Configuração e orientação sobre atualizações regulares de sistema operacional e aplicativos
· Instalação e configuração de antivírus ativo nos equipamentos da loja
· Definição e implementação de rotina de backup periódico (mídia externa ou nuvem)
· Configuração de bloqueio automático de tela e restrição de acesso físico ao computador.*

**Dentro do escopo:**
- *Implementação de política básica de cibersegurança com boas práticas (senhas fortes, não compartilhamento de acessos, cuidado com links suspeitos*
- *Configuração e orientação sobre atualizações regulares de sistema operacional e aplicativos*

**Fora do escopo:**
- *Aquisição ou substituição de equipamentos de hardware (computadores, roteadores, cabos)*
- *Desenvolvimento ou implantação de sistemas de gestão (ERP, PDV) ou softwares personalizados*

### 3.4 Tipo de Solução

*(Marque as opções que se aplicam ao seu projeto:)*

- [ ] Shell scripts para automação de tarefas de rede
- [ ] Back-end com API (.NET / outra tecnologia)
- [ ] Front-end web (HTML + CSS + JS)
- [ ] Aplicação móvel
- [ ] Configuração de infraestrutura de rede
- [x] Outro: *(Aplicação Google Sheets e API da Google)*
      

### 3.5 Justificativa Técnica

*As escolhas tecnológicas e metodológicas adotadas neste projeto foram orientadas pela realidade da Tavares Armarinhos, considerando seu porte (3 colaboradores), infraestrutura básica, baixo orçamento e limitado conhecimento técnico em TI.
1. Política de senhas fortes e autenticação em dois fatores (2FA)

· Adequação: Não exige hardware adicional nem investimento financeiro. Soluções como Google Authenticator ou Authy são gratuitas e compatíveis com os principais serviços (e-mail, redes sociais, sistemas de gestão).
· Manutenibilidade: Após a configuração inicial, exige apenas conscientização contínua, sem custos recorrentes.
· Nível técnico: A orientação será feita de forma prática e visual, com exemplos concretos de senhas e demonstração do 2FA.

2. Antivírus gratuito (ex.: Microsoft Defender, Kaspersky Free, Avast)

· Adequação: O Windows já possui o Microsoft Defender nativo e gratuito, com proteção em tempo real suficiente para o perfil de uso da loja (navegação, e-mail, controle de vendas).
· Manutenibilidade: Atualizações automáticas via Windows Update, sem necessidade de administração manual.
· Custo zero: Essencial para uma microempresa que não dispõe de verba para licenças pagas.

3. Backup periódico em mídia externa (HD externo ou pendrive) e/ou nuvem gratuita

· Adequação: HD externo de baixo custo (já disponível em muitos casos) ou serviços como Google Drive (15GB grátis) e OneDrive (5GB grátis) são suficientes para arquivos de controle de vendas e documentos administrativos.
· Simplicidade: O backup pode ser manual (uma vez por semana) com um lembrete visual, ou semiautomático usando ferramentas gratuitas como FreeFileSync.
· Manutenibilidade: Não requer servidores nem conhecimentos avançados.

4. Proteção de Wi-Fi com WPA2/WPA3 e alteração de credenciais padrão

· Adequação: Todos os roteadores residenciais já suportam WPA2 (e os mais novos WPA3). Alterar senha padrão e desabilitar WPS são ações simples, documentadas nos manuais do roteador.
· Impacto imediato: Elimina vulnerabilidades comuns como acesso indevido à rede por vizinhos ou ataques de força bruta.
· Manutenibilidade: Após configurado, só requer nova alteração em caso de esquecimento ou troca de funcionários.

5. Bloqueio automático de tela (após 5 minutos de inatividade)

· Adequação: Configuração nativa do Windows (via opções de energia/tela de bloqueio), sem custos.
· Necessidade real: Evita que um computador desacompanhado no balcão da loja seja acessado por terceiros.
· Nível técnico: A configuração é feita uma única vez e passa a operar de forma autônoma.

6. Atualizações automáticas do sistema e aplicativos

· Adequação: O Windows já possui atualizações automáticas por padrão. Para navegadores (Chrome, Firefox), também são automáticas.
· Justificativa de segurança: Corrige vulnerabilidades conhecidas sem depender do usuário lembrar de atualizar.
· Manutenibilidade: Zero esforço após verificação inicial de que as atualizações estão ativas.

7. Boas práticas de navegação (treinamento comportamental)

· Adequação: A principal vulnerabilidade em pequenos negócios é o erro humano (phishing, links suspeitos, downloads maliciosos). O treinamento custa apenas tempo e material impresso simples.
· Manutenibilidade: Recomenda-se um lembrete mensal e a fixação de um cartilha visual próxima ao computador.

Conclusão técnica: Todas as soluções escolhidas são de baixo ou nenhum custo, utilizam recursos já disponíveis no ambiente Windows e nos roteadores comuns, exigem baixo nível de conhecimento técnico para implementação e manutenção, e são escaláveis apenas no sentido de não sobrecarregarem a infraestrutura limitada da loja. O foco está em medidas de alto impacto com baixa complexidade, alinhadas à realidade de uma microempresa familiar.*

---

## 4. Requisitos

### 4.1 Requisitos Funcionais

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF01 | *O sistema deve permitir a configuração e aplicação de política de senhas fortes (mínimo 8 caracteres, incluindo letras maiúsculas, minúsculas, números e símbolos) para acesso aos equipamentos da loja. *| Alta |
| RF02 | * O antivírus (Microsoft Defender ou similar) deve estar ativo e com proteção em tempo real, realizando varreduras periódicas automaticamente.* | Alta |
| RF03 | *Deve ser implementada rotina de backup periódico (manual ou semiautomático) para mídia externa ou nuvem, com retenção mínima de 30 dias.* | Alta |

### 4.2 Requisitos Não Funcionais

| ID | Descrição | Categoria |
|----|-----------|-----------|
| RNF01 | *As soluções implementadas não devem gerar custos adicionais de software ou hardware (uso de ferramentas gratuitas e recursos nativos).* | *Viabilidade econômica* |
| RNF02 | *As configurações de segurança devem ser aplicáveis por pessoa com conhecimento básico em TI, com interface amigável e orientação visual.* |*Usabilidade* |

---

## 5. Arquitetura da Solução

*A arquitetura proposta é simplificada, de baixo custo e baseada em recursos já existentes no ambiente da loja. Não há servidores dedicados, infraestrutura em nuvem complexa ou sistemas personalizados.

5.1 Visão Geral da Topologia


<img width="1600" height="1060" alt="image" src="https://github.com/user-attachments/assets/41869a3c-6846-4cea-bacc-88b391e90b0c" />


5.2 Componentes da Arquitetura

Componente Tecnologia/Configuração Papel na Segurança
Roteador/Modem Configuração manual: WPA2/WPA3, troca de senha padrão, desativação de WPS, atualização de firmware Proteção do perímetro de rede contra acessos indevidos
Computador da loja Windows 10/11 (ou versão suportada) Estação de trabalho principal para controle de vendas, e-mail e navegação
Antivírus Microsoft Defender (nativo do Windows) ou Kaspersky Free / Avast Free Proteção em tempo real contra malware e ameaças
Backup Mídia externa (HD/USB) + Google Drive (15GB grátis) ou OneDrive (5GB) Recuperação de dados em caso de falha, ransomware ou erro humano
Gerenciamento de senhas Política manual + opcional: ferramenta gratuita como Bitwarden (versão pessoal) Evita reuso de senhas e acesso não autorizado
Políticas de segurança Configuração local do Windows (usuário padrão sem admin, bloqueio de tela, UAC ativo) + treinamento Redução de superfície de ataque e conscientização.

5.3 Diagrama Conceitual (descrição para implementação)

<img width="1414" height="1600" alt="WhatsApp Image 2026-05-12 at 11 43 36" src="https://github.com/user-attachments/assets/5ab7dd78-63e4-435e-916a-7f5484431cbd" />


5.4 Fluxo de Manutenção

· Diário: Nenhuma ação técnica necessária (bloqueio de tela automático).
· Semanal: Backup manual (ou plugar HD externo e executar script simples).
· Mensal: Verificar se as atualizações automáticas estão sendo aplicadas (via Windows Update). Conferir logs do antivírus.
· Trimestral / Sob demanda: Reforço do treinamento rápido (10 minutos) com os colaboradores.

---

## 6. Cronograma do Projeto

| Atividade | Responsável | Início | Fim | Status |
|-----------|-------------|--------|-----|--------|
| Levantamento de requisitos | *Andrew* | *24/02/2026* | *28/02/2026* | *Concluído* |
| Prototipação | *Geraldo* | *01/03/2026* | *03/03/2026* | *Concluído* |
| Desenvolvimento do servidor | *Andrew, Geraldo, André, Daniel* | *08/04/2026)* | *20/04/2026* | *Concluído* |
| Desenvolvimento do cliente | *Andrew, Geraldo, André, Daniel* | *01/05/2026* | *11/05/2026* | *Concluído* |
| Testes | *(Nome)* | *(Data)* | *(Data)* | *(Status)* |
| Documentação | *(Nome)* | *(Data)* | *(Data)* | *(Status)* |
| Apresentação | *(Nome)* | *(Data)* | *(Data)* | *(Status)* |

---

## 7. Riscos Identificados

| Risco | Probabilidade | Impacto | Mitigação |
|-------|--------------|---------|-----------|
| *(Descrição do risco)* | Alta / Média / Baixa | Alto / Médio / Baixo | *(Ação de mitigação)* |
| *(Descrição do risco)* | *(Prob.)* | *(Imp.)* | *(Mitigação)* |
