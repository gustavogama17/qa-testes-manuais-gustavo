# Caso de Teste TC-001 – Login com credenciais válidas (SauceDemo)

**Aplicação:** SauceDemo – página de login  
**URL:** https://www.saucedemo.com  
**Tipo de teste:** Funcional – Manual  
**Objetivo:** Verificar se o sistema permite o login com credenciais válidas e redireciona o usuário para a página de produtos.

---

## Pré-condições

- Ter acesso à internet.
- Navegador aberto (Chrome, Firefox ou similar).
- Site https://www.saucedemo.com disponível.
- Credenciais de teste fornecidas pela aplicação:
  - Usuário: `standard_user`
  - Senha: `secret_sauce`

---

## Passos para execução

1. Acessar a URL `https://www.saucedemo.com` no navegador.
2. Localizar o campo **Username**.
3. Preencher o campo **Username** com `standard_user`.
4. Localizar o campo **Password**.
5. Preencher o campo **Password** com `secret_sauce`.
6. Clicar no botão **Login**.

---

## Dados de teste

- **Username:** `standard_user`  
- **Password:** `secret_sauce`

---

## Resultado esperado

- O sistema deve autenticar o usuário.
- O usuário deve ser redirecionado para a página **"Products"**.
- A URL deve mudar para algo como `https://www.saucedemo.com/inventory.html`.
- Deve ser exibida uma lista de produtos na tela.

---

## Resultado obtido

> (Preencher após execução manual do teste)

---

## Status

- **Passou / Falhou** (selecionar após execução)

---

## Observações

> (Registrar qualquer comportamento diferente, lentidão, mensagem de erro inesperada etc.)
