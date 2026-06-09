# Relatório da Disciplina de Extensão

> Relatório final da atividade extensionista desenvolvida no âmbito da disciplina de Desenvolvimento de Sistema para Redes de Computadores, conforme exigências da curricularização da extensão (Resolução CNE/CES nº 7/2018).

---

## 1. Dados da Atividade

| Campo | Descrição |
|-------|-----------|
| **Instituição** | Pontifícia Universidade Católica de Minas Gerais (PUC Minas) |
| **Curso** | Curso Superior de Tecnologia em Redes de Computadores |
| **Disciplina** | Desenvolvimento de Sistema para Redes de Computadores |
| **Eixo** | 3 |
| **Semestre/Ano** | *3° Semestre 2026*  |
| **Professor(a) orientador(a)** | *Harison Herman Silva* |
| **Carga horária de extensão** | *(Preencher conforme PPC)* |

---

## 2. Equipe Executora

| Nome Completo | Matrícula | E-mail Institucional |
|---------------|-----------|----------------------|
| *Geraldo Rodrigues* | *883066* | *geraldo.goncalves@sga.pucminas.br* |
| *André Albuquerque* | *1582764* | *aalbuquerque@sga.pucminas.br* |
| *Andrew Tavares* | *895540* | *andrew.monteiro@sga.pucminas.br* |
| *Daniel Ferreira* | *880944* | *daniel.ferreira@sga.pucminas.br* |
| *Maria Eduarda* | *1510644* | *maria.reis@sga.pucminas.br* |

---

## 3. Comunidade Parceira

| Campo | Descrição |
|-------|-----------|
| **Nome** | *Armarinho Tavares* |
| **Tipo** | *Empresa* |
| **Endereço** | *Rua Claudinei de Oliveira Silva, 166 Francisco Morato São Paulo - SP* |
| **Responsável** | *Adriana, Gerente* |
| **Contato** | *armarinhostavares@gmail.com 11 94500-6561 * |
| **Público atendido** | *Usuários da Rede, Vendedores - Gerência e Outros - Quantidade estimada 6 pessoas* |

---

## 4. Resumo da Atividade

*Problema identificado:
O Armarinhos Tavares, microempresa de Francisco Morato/SP, operava com infraestrutura de TI básica, utilizando conexão residencial sem diretrizes formais de segurança. Foram identificadas vulnerabilidades críticas: ausência de controle de acesso, inexistência de rotinas de backup, falta de antivírus ativo, senhas fracas e rede Wi-Fi desprotegida. Essas falhas expunham os dados da loja a riscos como perda de informações, acesso não autorizado e ameaças virtuais (malware, phishing).

Solução proposta:
Implementação de uma política de cibersegurança de baixo custo e alto impacto, utilizando recursos já disponíveis. As ações incluíram: adoção de senhas fortes e autenticação em dois fatores; ativação do Microsoft Defender com proteção em tempo real; configuração de backup semanal em HD externo e nuvem gratuita (Google Drive); proteção da rede Wi-Fi com criptografia WPA2/WPA3 e alteração de credenciais padrão; bloqueio automático de tela após inatividade; e treinamento dos colaboradores em boas práticas de navegação (phishing, links suspeitos).

Ações realizadas:
Foram configurados os equipamentos existentes (computador com Windows, roteador), aplicadas as políticas de segurança, estabelecida rotina de backups e produzido material visual de conscientização. Todo o processo foi documentado com termos de parceria e evidências.

Resultados alcançados:
Redução significativa das vulnerabilidades operacionais; proteção dos dados da loja contra perda e acessos indevidos; maior estabilidade e confiança nas atividades diárias; conscientização dos colaboradores sobre riscos digitais; e nenhum custo adicional com software ou hardware, garantindo viabilidade e sustentabilidade para o pequeno negócio.*

---

## 5. Objetivos

### 5.1 Objetivo Geral

Implementar uma política básica de cibersegurança na loja Tavares Armarinhos, visando reduzir vulnerabilidades, proteger dados sensíveis e garantir maior estabilidade, segurança e confiabilidade nas operações diárias, por meio de ações práticas e de baixo custo, como gestão de senhas, backups periódicos, proteção da rede Wi-Fi e adoção de boas práticas de navegação.

5.2 Objetivos Específicos

1. Realização de Backup – Estabelecer rotina semanal de backup dos dados da loja em mídia externa (HD ou pendrive) e/ou nuvem gratuita (Google Drive ou OneDrive), garantindo retenção mínima de 30 dias para recuperação em caso de falhas ou ataques.
2. Implementação de Políticas de Segurança – Configurar bloqueio automático de tela após inatividade, restringir acessos físicos ao computador e aplicar princípios de menor privilégio (usuário padrão sem administrador).
3. Gestão de Senhas – Adotar senhas fortes (mínimo 8 caracteres com letras maiúsculas, minúsculas, números e símbolos), evitar reuso e compartilhamento, e implementar autenticação em dois fatores (2FA) nos principais serviços.
4. Adoção de boas práticas de Navegação – Treinar os colaboradores para identificar links suspeitos, e-mails de phishing e downloads maliciosos, fixando material visual de apoio próximo ao computador.

---

6. Fundamentação Teórica

O presente projeto fundamenta-se em conceitos clássicos de segurança da informação e boas práticas de TI, alinhados aos microfundamentos estudados ao longo do curso.

Microfundamento: Gerência de Projetos de T.I. – A implementação da política de cibersegurança seguiu as fases de um projeto: levantamento de requisitos (identificação das vulnerabilidades da loja), planejamento (definição de escopo, objetivos e cronograma), execução (configurações e treinamentos), monitoramento (verificação de backups e atualizações) e encerramento (entrega da documentação e termo de parceria). Essa abordagem garantiu entregas controladas e alinhadas à realidade da microempresa.

Microfundamento: Teste e Manutenção de Software – Embora não tenha sido desenvolvido software novo, a manutenção contínua dos sistemas existentes (Windows, antivírus, navegadores) é essencial para a segurança. Foram validadas as atualizações automáticas do sistema operacional e aplicativos, e definidos ciclos de verificação mensal dos logs do antivírus e da integridade dos backups, assegurando que as soluções permaneçam funcionais ao longo do tempo.

Microfundamento: APIs e Web Services (relação indireta) – O uso de serviços em nuvem gratuitos (Google Drive e OneDrive) para armazenamento de backups envolve, indiretamente, o consumo de APIs RESTful dessas plataformas. Embora o projeto não exija desenvolvimento de integração personalizada, compreender o funcionamento de APIs permite, futuramente, automatizar o processo de backup via scripts (ex.: Google Drive API).

Microfundamento: Desenvolvimento Web Backend e Front End – A política de segurança inclui orientações sobre navegação segura, que envolvem a proteção contra ameaças web como phishing e XSS. O treinamento aborda como identificar URLs maliciosas e formulários falsos, conceitos diretamente relacionados à segurança no desenvolvimento de aplicações web (tanto backend quanto frontend).

Microfundamento: Desenvolvimento de Aplicações Móveis – A recomendação de autenticação em dois fatores (2FA) utiliza aplicativos móveis como Google Authenticator ou Authy, demonstrando como dispositivos móveis podem atuar como fatores de autenticação independentes, aumentando significativamente a segurança contra acessos não autorizados.

Conclusão teórica: O projeto aplica os princípios da tríade CID (Confidencialidade, Integridade e Disponibilidade) – confidencialidade via senhas e bloqueio de tela; integridade via backups e antivírus; disponibilidade via atualizações e manutenção preventiva. Todos os microfundamentos contribuem para a formação de uma visão sistêmica, onde a segurança não depende apenas de tecnologia, mas também de processos e pessoas.
---

## 7. Metodologia

*(Descreva a metodologia utilizada para o desenvolvimento do projeto. Inclua: como foi o processo de levantamento de requisitos, as etapas de desenvolvimento, as tecnologias utilizadas, as visitas à comunidade, os métodos de validação, etc.)*

---

## 8. Cronograma Executado

| Atividade | Período Planejado | Período Executado | Observações |
|-----------|-------------------|-------------------|-------------|
| Contato inicial com a comunidade | *(Data)* | *(Data)* | *(Obs.)* |
| Levantamento de requisitos | *(Data)* | *(Data)* | *(Obs.)* |
| Especificação e prototipação | *(Data)* | *(Data)* | *(Obs.)* |
| Desenvolvimento do back-end | *(Data)* | *(Data)* | *(Obs.)* |
| Desenvolvimento do front-end | *(Data)* | *(Data)* | *(Obs.)* |
| Testes e ajustes | *(Data)* | *(Data)* | *(Obs.)* |
| Documentação | *(Data)* | *(Data)* | *(Obs.)* |
| Apresentação | *(Data)* | *(Data)* | *(Obs.)* |

---

## 9. Resultados Alcançados

*(Descreva os resultados obtidos com o projeto. Inclua resultados técnicos (o que foi entregue), resultados para a comunidade (como a solução impactou) e resultados para os alunos (aprendizados).)*

### 9.1 Resultados Técnicos

*(Preencher)*

### 9.2 Resultados para a Comunidade

*(Preencher)*

### 9.3 Resultados para a Formação dos Alunos

*(Preencher)*

---

## 10. Dificuldades Encontradas

*(Relate as dificuldades encontradas durante a execução do projeto e como foram contornadas.)*

---

## 11. Conclusão

*(Apresente as conclusões do grupo sobre a experiência extensionista, o alcance dos objetivos e as contribuições do projeto tanto para a comunidade quanto para a formação dos alunos.)*

---

## 12. Registro de Interações com a Comunidade

> Liste todas as interações (visitas, reuniões, chamadas, e-mails relevantes) realizadas com a comunidade parceira.

| Data | Tipo de Interação | Participantes | Descrição | Evidência |
|------|-------------------|---------------|-----------|-----------|
| *(dd/mm/aaaa)* | *(Visita/Reunião/Chamada/E-mail)* | *(Nomes)* | *(Breve descrição)* | *(Referência a foto/ata em evidencias/)* |
| *(dd/mm/aaaa)* | *(Tipo)* | *(Nomes)* | *(Descrição)* | *(Referência)* |

---

## 13. Referências

*(Liste as referências bibliográficas, técnicas e de microfundamentos utilizadas.)*

---

## 14. Anexos

*(Liste os documentos anexos ao relatório, referenciando os arquivos nas pastas do repositório.)*

| Anexo | Descrição | Localização no Repositório |
|-------|-----------|----------------------------|
| Termo de parceria | Termo assinado com a comunidade | `evidencias/termos/` |
| Atas de reunião | Atas das reuniões com a comunidade | `evidencias/atas/` |
| Registro fotográfico | Fotos das visitas e atividades | `evidencias/fotos/` |
| Depoimentos | Depoimentos dos membros da comunidade | `evidencias/depoimentos/` |

---

> **Nota:** Este relatório é um documento oficial da atividade extensionista e poderá ser utilizado para comprovação junto ao MEC. Preencha com atenção e inclua todas as evidências solicitadas.
