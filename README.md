# Sistema de Registro de Presença

## Descrição do Projeto

Este projeto é um sistema simples para registro de presença em aula. O aluno realiza o login utilizando seu código de aluno (RA), e o sistema captura o horário atual e a localização do usuário para enviar automaticamente a informação de presença ao professor responsável. O sistema oferece duas opções de login: aluno e professor. Após o login do aluno, as informações de presença são enviadas e disponibilizadas para o professor, que pode visualizar as presenças registradas.

## Requisitos Funcionais

- RF1: Permitir que o usuário realize login como aluno ou professor.
- RF2: Para o aluno, capturar o código RA, horário atual e localização do dispositivo.
- RF3: Enviar os dados de presença (RA, horário, localização) para o professor correspondente.
- RF4: Permitir que o professor visualize a lista de presenças enviadas pelos alunos.
- RF5: Validar que o horário de presença esteja dentro do período permitido da aula.

## Requisitos Não Funcionais

- RNF1: O sistema deve garantir a segurança dos dados pessoais dos alunos e professores.
- RNF2: A interface deve ser simples e responsiva para uso em dispositivos móveis.
- RNF3: O sistema deve apresentar alta disponibilidade durante o horário de aula.
- RNF4: As informações devem ser enviadas e recebidas com baixa latência.
- RNF5: O sistema deve respeitar a privacidade do usuário quanto à localização, solicitando permissões antes da captura.

---

Este projeto visa facilitar o controle de presença e agilizar a comunicação entre alunos e professores, utilizando tecnologias básicas para autenticação, geolocalização e registro de horários.
