# Caso de Teste TC-002 – Adicionar novo registro na Web Table (DemoQA)

**Aplicação:** DemoQA – Web Tables  
**URL:** https://demoqa.com/webtables  
**Tipo de teste:** Funcional – Manual  
**Objetivo:** Verificar se o sistema permite adicionar um novo registro à tabela e exibi-lo corretamente na lista.

---

## Pré-condições

- Ter acesso à internet.
- Navegador aberto.
- Site https://demoqa.com/webtables disponível.

---

## Passos para execução

1. Acessar a URL `https://demoqa.com/webtables` no navegador.
2. Localizar e clicar no botão **Add** (para adicionar novo registro).
3. Na janela de formulário que abrir, preencher os campos:
   - **First Name:** `Gustavo`
   - **Last Name:** `Cruz`
   - **Email:** `gustavo.cruz@test.com`
   - **Age:** `29`
   - **Salary:** `1500`
   - **Department:** `QA`
4. Clicar no botão **Submit**.

---

## Dados de teste

- **First Name:** `Gustavo`  
- **Last Name:** `Cruz`  
- **Email:** `gustavo.cruz@test.com`  
- **Age:** `29`  
- **Salary:** `1500`  
- **Department:** `QA`

---

## Resultado esperado

- A janela de formulário deve ser fechada após clicar em **Submit**.
- Um novo registro deve ser exibido na tabela principal.
- A linha incluída deve conter os dados:
  - `Gustavo` | `Cruz` | `29` | `gustavo.cruz@test.com` | `1500` | `QA`

---

## Resultado obtido

> (Preencher após execução manual do teste)

---

## Status

- **Passou / Falhou**

---

## Observações

> (Registrar se o registro não aparecer, se os valores forem truncados, se houver erro de validação etc.)
