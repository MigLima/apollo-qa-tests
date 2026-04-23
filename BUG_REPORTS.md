# Bug Reports

## BUG001 - Falha ao exibir erro no login

**Severidade:** Média  
**Prioridade:** Alta  

**Passos:**
1. Inserir email válido
2. Inserir senha incorreta
3. Clicar em "Entrar"

**Resultado atual:**
Sistema não exibe mensagem de erro

**Resultado esperado:**
Sistema deve informar que a senha está incorreta

---

## BUG002 - Email inválido aceito

**Severidade:** Baixa  
**Prioridade:** Média  

**Passos:**
1. Inserir "teste@"
2. Submeter formulário

**Resultado atual:**
Sistema aceita email inválido

**Resultado esperado:**
Sistema deve validar o formato do email
