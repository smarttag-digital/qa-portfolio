# Casos de Teste — Projeto 02: Cadastro

**Sistema:** Automation Exercise  
**Módulo:** Cadastro de usuário  
**Ambiente:** https://www.automationexercise.com/signup

---

### CT001 — Cadastro com dados válidos

- **Resultado esperado:** O sistema deve criar a conta e apresentar uma mensagem de confirmação.
- **Resultado obtido:** O sistema criou a conta e apresentou a mensagem "Account Created!".
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT001](evidencias/CT001-cadastro-sucesso.png)

### CT002 — Cadastro sem nome

- **Resultado esperado:** O sistema deve impedir o avanço e solicitar o preenchimento do campo nome.
- **Resultado obtido:** O navegador apresentou um aviso solicitando que o nome fosse informado.
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT002](evidencias/CT002-nome-vazio.png)

### CT003 — Cadastro sem e-mail

- **Resultado esperado:** O sistema deve impedir o envio e solicitar o preenchimento do campo e-mail.
- **Resultado obtido:** O navegador apresentou a mensagem "Preencha este campo", impedindo o envio do formulário.
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT003](evidencias/CT003-email-vazio.png)

### CT004 — Cadastro com e-mail inválido

- **Resultado esperado:** O sistema deve impedir o envio de um endereço de e-mail em formato inválido.
- **Resultado obtido:** O navegador apresentou uma mensagem de validação solicitando a inclusão do caractere @.
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT004](evidencias/CT004-email-invalido.png)

### CT005 — Cadastro com e-mail já existente

- **Resultado esperado:** O sistema deve impedir o cadastro de um endereço de e-mail já registrado.
- **Resultado obtido:** O sistema bloqueou o cadastro e apresentou a mensagem "Email Address already exist!".
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT005](evidencias/CT005-email-duplicado.png)

### CT006 — Cadastro sem senha

- **Resultado esperado:** O sistema deve impedir o envio do cadastro e solicitar o preenchimento do campo senha.
- **Resultado obtido:** O navegador apresentou a mensagem "Preencha esse campo", impedindo o envio do cadastro sem senha.
- **Status:** PASSOU.
- **Evidência:** [Visualizar captura CT006](evidencias/CT006-senha-vazia.png)
