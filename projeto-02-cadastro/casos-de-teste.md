


### CT001 — Cadastro com dados válidos

- Resultado esperado: O sistema deve criar a conta e apresentar uma mensagem de confirmação.
- Resultado obtido: O sistema criou a conta e apresentou a mensagem "Account Created!".
- Status: PASSOU.
- Evidência: [Visualizar captura CT001](evidencias/CT001-cadastro-sucesso.png)


### CT002 — Cadastro sem nome

- Resultado esperado: O sistema deve impedir o avanço e solicitar o preenchimento do nome.
- Resultado obtido: O navegador apresentou um aviso solicitando que o nome fosse informado.
- Status: PASSOU.
- Evidência: [Visualizar captura CT002](evidencias/CT002-nome-vazio.png)

- ### CT003 — Cadastro sem e-mail

- Resultado esperado: O sistema deve impedir o envio e solicitar o preenchimento do e-mail.
- Resultado obtido: O navegador apresentou a mensagem "Preencha este campo".
- Status: PASSOU.
- Evidência: [Visualizar captura CT003](evidencias/CT003-email-vazio.png)

- ### CT004 — Cadastro com e-mail inválido

- Resultado esperado: O sistema deve impedir o envio de um endereço de e-mail em formato inválido.
- Resultado obtido: O navegador apresentou a mensagem solicitando a inclusão do caractere @.
- Status: PASSOU.
- Evidência: [Visualizar captura CT004](evidencias/CT004-email-invalido.png)

- ### CT005 — Cadastro com e-mail já existente

- Resultado esperado: O sistema deve impedir o cadastro de um e-mail já registrado.
- Resultado obtido: O sistema bloqueou o cadastro e apresentou a mensagem "Email Address already exist!".
- Status: PASSOU.
- Evidência: [Visualizar captura CT005](evidencias/CT005-email-duplicado.png)

- 
