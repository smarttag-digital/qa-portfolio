# Projeto 01 — Casos de Teste de Login

## Objetivo
Verificar se a funcionalidade de login apresenta o comportamento esperado em diferentes situações.

## Casos de Teste

### CT001 — Login com credenciais válidas
- Pré-condição: possuir uma conta cadastrada.
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail válido.
  3. Informar uma senha válida.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve permitir o acesso.
- - Status: PASSOU (Pass).
- Resultado obtido: O sistema permitiu o acesso e abriu a página de produtos.

### CT002 — Login com senha incorreta
- Pré-condição: possuir uma conta cadastrada.
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail válido.
  3. Informar uma senha incorreta.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve bloquear o acesso e apresentar uma mensagem adequada.
- Status: Passou (Pass)
- Resultado obtido: O sistema bloqueou o acesso ao informar uma senha incorreta.
- Mensagem apresentada: Epic sadface: Username and password do not match any user in this service

### CT003 — Login com e-mail vazio
- Passos:
  1. Acessar a tela de login.
  2. Deixar o campo de e-mail vazio.
  3. Informar uma senha.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve solicitar o preenchimento do e-mail.
- Status: PASSOU (Pass).
- Resultado obtido: O sistema bloqueou o acesso quando o campo de usuário foi deixado vazio.
- Mensagem apresentada: Epic sadface: Username is required
  

### CT004 — Login com senha vazia
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail válido.
  3. Deixar o campo de senha vazio.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve solicitar o preenchimento da senha.
- Status: PASSOU (Pass).
- Resultado obtido: O sistema bloqueou o acesso quando o campo de senha foi deixado vazio.
- Mensagem apresentada: Epic sadface: Password is required

### CT005 — Login com e-mail em formato inválido
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail em formato inválido.
  3. Informar uma senha.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve validar o formato do e-mail e impedir o envio dos dados inválidos.
- Status: PASSOU.
- Resultado obtido: O sistema bloqueou o acesso ao utilizar um nome de usuário inexistente.
- Mensagem apresentada: Epic sadface: Username and password do not match any user in this service.
