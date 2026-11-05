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
- Status: Não executado.

### CT002 — Login com senha incorreta
- Pré-condição: possuir uma conta cadastrada.
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail válido.
  3. Informar uma senha incorreta.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve bloquear o acesso e apresentar uma mensagem adequada.
- Status: Não executado.

### CT003 — Login com e-mail vazio
- Passos:
  1. Acessar a tela de login.
  2. Deixar o campo de e-mail vazio.
  3. Informar uma senha.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve solicitar o preenchimento do e-mail.
- Status: Não executado.

### CT004 — Login com senha vazia
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail válido.
  3. Deixar o campo de senha vazio.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve solicitar o preenchimento da senha.
- Status: Não executado.

### CT005 — Login com e-mail em formato inválido
- Passos:
  1. Acessar a tela de login.
  2. Informar um e-mail em formato inválido.
  3. Informar uma senha.
  4. Clicar em Entrar.
- Resultado esperado: o sistema deve validar o formato do e-mail e impedir o envio dos dados inválidos.
- Status: Não executado.
