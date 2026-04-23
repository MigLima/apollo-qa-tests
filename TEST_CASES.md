# Test Cases

## TC001 - Login com dados válidos

**Pré-condição:** Usuário cadastrado

**Passos:**
1. Acessar tela de login
2. Inserir email válido
3. Inserir senha válida
4. Clicar em "Entrar"

**Resultado esperado:**
Usuário deve acessar a tela inicial

---

## TC002 - Login com senha inválida

**Pré-condição:** Usuário cadastrado

**Passos:**
1. Inserir email válido
2. Inserir senha incorreta
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem de erro

---

## TC003 - Recuperação de senha

**Passos:**
1. Acessar "Esqueci minha senha"
2. Inserir email válido
3. Confirmar

**Resultado esperado:**
Sistema deve enviar instruções para o email
