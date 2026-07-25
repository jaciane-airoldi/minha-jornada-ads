# 📋 Casos de Teste - Funcionalidade Login

## Caso de Teste 01

### Cenário:
Login com usuário e senha válidos.

### Passos:
1. Acessar a tela de login.
2. Informar usuário válido.
3. Informar senha válida.
4. Clicar no botão "Entrar".

### Resultado esperado:
Usuário deve acessar o sistema com sucesso.

### Status:
✅ Aprovado

---

## Caso de Teste 02

### Cenário:
Login com senha inválida.

### Passos:
1. Informar usuário válido.
2. Informar senha incorreta.
3. Clicar no botão "Entrar".

### Resultado esperado:
Sistema deve informar que os dados estão incorretos.

### Status:
🧪 Em validação

---

## Caso de Teste 03

### Cenário:
Tentativa de login sem preencher senha.

### Passos:
1. Informar usuário válido.
2. Deixar o campo senha vazio.
3. Clicar no botão "Entrar".

### Resultado esperado:
Sistema deve informar que a senha é obrigatória.

### Status:
🐞 Bug identificado