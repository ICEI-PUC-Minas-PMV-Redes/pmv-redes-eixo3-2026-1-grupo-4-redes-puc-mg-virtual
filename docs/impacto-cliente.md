# Análise do Impacto da Solução no Cliente

> Este documento analisa o impacto que a solução desenvolvida pelo grupo teve (ou terá) na comunidade parceira. É um dos documentos requeridos para comprovação da atividade extensionista.

---

## 1. Identificação

| Campo | Descrição |
|-------|-----------|
| **Comunidade parceira** | *Armarinho Tavares / Loja de Material - Depósito* |
| **Projeto desenvolvido** | *Implantação de Políticas de Segurança* |
| **Período de execução** | *24/02/2026 – 30/06/2026* |
| **Número de pessoas diretamente impactadas** | *3* |
| **Número de pessoas indiretamente impactadas** | *6* |

---

## 2. Situação Anterior (Antes do Projeto)

*Antes da intervenção, a loja Armarinhos Tavares operava com infraestrutura de TI básica e sem diretrizes formais de segurança digital. Os principais problemas identificados foram:

· Conexão residencial sem proteção adequada, com senha do Wi-Fi fraca e credenciais padrão do roteador mantidas.
· Ausência de política de senhas – colaboradores usavam senhas curtas, repetidas e frequentemente compartilhadas.
· Nenhuma rotina de backup – dados de controle de vendas e documentos fiscais ficavam apenas no computador da loja.
· Antivírus desatualizado ou inativo – o Microsoft Defender estava desabilitado em alguns momentos por falta de conhecimento.
· Bloqueio automático de tela desativado – computador permanecia acessível mesmo quando o balcão ficava desatendido.
· Falta de treinamento. Colaboradores não sabiam identificar e-mails de phishing ou links suspeitos.

Essas vulnerabilidades geravam riscos concretos de perda de dados, acesso indevido à rede e possível comprometimento do computador usado para vendas e comunicação.*

---

## 3. Solução Implementada

*Foi implementada uma política básica de cibersegurança com as seguintes ações:

· Gestão de senhas: definição de senhas fortes (mínimo 8 caracteres com letras maiúsculas, minúsculas, números e símbolos) para o computador da loja. Orientação sobre não compartilhamento de acessos.
· Antivírus ativo: ativação e configuração do Microsoft Defender com proteção em tempo real e varreduras automáticas.
· Backup periódico: rotina semanal de backup manual para pendrive/HD externo, com orientação para manter uma cópia desconectada após o procedimento.
· Proteção da rede Wi-Fi: alteração da senha padrão do roteador, configuração de criptografia WPA2/WPA3 e desativação do WPS.
· Bloqueio automático de tela: configurado para ativar após 5 minutos de inatividade.
· Atualizações automáticas: verificação e habilitação do Windows Update e atualizações automáticas dos navegadores.
· Treinamento comportamental: fixação de cartilha visual próxima ao computador com boas práticas (cuidado com links suspeitos, phishing, downloads).

Tecnologias utilizadas: recursos nativos do Windows (Defender, bloqueio de tela, Windows Update), configuração manual do roteador, pendrive/HD externo para backup, e material impresso para conscientização.
*

---

## 4. Situação Posterior (Após o Projeto)

*Após a implementação da solução, a loja passou a operar com um nível básico, porém efetivo, de segurança digital:

· Computador da loja agora requer senha forte para acesso e bloqueia automaticamente quando ausente.
· Rede Wi-Fi está protegida com criptografia forte e senha robusta, eliminando acessos indevidos de vizinhos ou visitantes.
· Backup semanal garante que os dados de vendas e documentos fiscais possam ser recuperados em caso de falha do computador ou ataque de ransomware.
· Antivírus ativo monitora ameaças em tempo real, reduzindo risco de infecção por arquivos maliciosos.
· Colaboradores receberam treinamento prático e passaram a reconhecer e evitar e-mails suspeitos e links perigosos.

A rotina diária não foi impactada negativamente – as medidas são automáticas (antivírus, bloqueio de tela, atualizações) ou demandam poucos minutos por semana (backup).*

---

## 5. Análise de Impacto

### 5.1 Impactos Positivos

Aspecto Impacto Observado
Segurança de dados Os dados de controle de vendas e documentos administrativos passaram a ter backup regular, eliminando o risco de perda irreversível por falha de hardware ou erro humano.
Proteção contra acessos indevidos Com senha forte no computador, bloqueio de tela e Wi-Fi protegido, reduziu-se drasticamente a chance de acesso não autorizado por terceiros (clientes, vizinhos ou visitantes).
Prevenção contra malware O antivírus ativo e atualizado, combinado com boas práticas de navegação, diminui a exposição a ransomware, phishing e outros tipos de malware comuns em pequenos comércios.
Capacitação tecnológica Os 3 colaboradores foram treinados em conceitos básicos de cibersegurança, adquirindo autonomia para identificar ameaças e manter as boas práticas mesmo sem acompanhamento externo.
Custo zero Todas as soluções implementadas utilizaram recursos gratuitos (Microsoft Defender, Windows Update, configurações nativas) ou materiais de baixo custo (pendrive/HD externo já disponível, cartilha impressa).
Continuidade das operações Em caso de incidente (falha do computador, arquivo corrompido, ataque), o backup permite restaurar os dados em poucos minutos, evitando paralisação do atendimento (média de 30 atendimentos/dia).

Pontos de melhoria futura:

· Automatizar o backup com ferramenta gratuita como FreeFileSync ou agendador de tarefas do Windows.
· Ativar 2FA no e-mail principal da loja (Gmail) e em qualquer sistema de gestão utilizado.
· Realizar lembretes mensais (via WhatsApp ou e-mail) sobre boas práticas, por iniciativa do proprietário ou gerente.
· Avaliar a possibilidade de aquisição futura de um roteador com suporte a rede de convidados, em caso de expansão do negócio.*

| Aspecto | Impacto Observado |
|---------|-------------------|
| *Conectividade* | *Impacto positivo na melhora da conexão e segurançã da Rede* |
| *Eficiência operacional* | *Eficiência operacional Backup semanal evita paralisação dos 30 atendimentos/dia por perda de dados. Antivírus e bloqueio de tela mantêm o computador sempre rápido e seguro sem intervenção manual.* |
| *Capacitação tecnológica* | *Os 3 colaboradores aprenderam a identificar phishing, criar senhas fortes e fazer backup, tornando-se autônomos para manter a segurança sem suporte externo.* |

### 5.2 Limitações e Pontos de Melhoria

*Limitações identificadas:
· O backup ainda é manual (semanal). Se o colaborador esquecer de realizá-lo, os dados ficam desprotegidos até a semana seguinte.
· Não há autenticação em dois fatores (2FA) ativa nos serviços web utilizados pela loja (e-mail, redes sociais), pois depende da adesão da equipe.
· O treinamento comportamental depende de reforço contínuo para não ser esquecido com o tempo.
· Não foi implementada uma rede separada para convidados, caso o roteador suporte, o que seria desejável para isolar dispositivos de clientes.*

### 5.3 Sustentabilidade da Solução

*A solução foi projetada para ser mantida pela própria loja com mínimo esforço:

· Capacitação local: os 3 colaboradores receberam treinamento prático e a cartilha fixada próxima ao computador serve como lembrete visual contínuo.
· Custos recorrentes: zero – todas as ferramentas são gratuitas (Microsoft Defender, Windows Update, backups para mídia externa). Se optarem por nuvem no futuro, planos gratuitos (Google Drive 15GB, OneDrive 5GB) são suficientes.
· Manutenção técnica: não há necessidade de suporte especializado. As configurações (bloqueio de tela, antivírus, atualizações automáticas) operam de forma autônoma após configuração inicial.
· Backup: recomenda-se que a própria gerente (Adriana) assuma a responsabilidade semanal, colocando um lembrete no celular ou na agenda da loja.
· Riscos de abandono: o único risco é a rotina de backup manual ser esquecida. Para mitigar, sugeriu-se um calendário impresso próximo ao computador para marcar cada backup realizado.

Conclusão sobre sustentabilidade: A comunidade parceira tem plenas condições de manter a solução funcionando após a saída do grupo, pois não depende de tecnologia complexa, custos recorrentes ou conhecimento técnico avançado. A continuidade depende basicamente da disciplina da equipe em realizar o backup semanal, o que foi comunicado e acordado com a gerente durante o projeto.*


## 6. Feedback da Comunidade

*(Registre depoimentos e feedbacks recebidos de membros da comunidade parceira sobre a solução implementada. Inclua citações diretas quando autorizadas.)*

**Depoimento 1:**
> *Após a impalantação das políticas de segurança, tivemos uma melhora nos processos e na disponibilidade da Rede e da Internet.* – ***(José Viana, Vendedor)***

**Depoimento 2:**
> *Com a aplicação das politicas de Segurança e o Backup temos mais confiança na Rede e no Sistema, até mesmo nossa navegação ficou mais rápida* – ***(Adriana, Gerente)***

---

## 7. Indicadores Quantitativos (se aplicável)

| Indicador | Antes | Depois | Variação |
|-----------|-------|--------|----------|
| *(Ex: Tempo médio de resolução de problemas de rede)* | *(Valor)* | *(Valor)* | *(%)* |
| *(Ex: Número de dispositivos conectados)* | *(Valor)* | *(Valor)* | *(%)* |
| *(Ex: Disponibilidade da rede)* | *(Valor)* | *(Valor)* | *(%)* |

---

## 8. Registro Fotográfico

*(Referencie as fotos incluídas na pasta `evidencias/fotos/` que comprovam o impacto da solução.)*

| Foto | Descrição | Data |
|------|-----------|------|
| `evidencias/fotos/*(nome_arquivo)*` | *(Descrição da foto)* | *(Data)* |

---

> **Nota:** Este documento serve como comprovação para fins de extensão universitária (MEC). Seja detalhado e inclua evidências sempre que possível.
