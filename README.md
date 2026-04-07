# Sistema Calculadora

---

## ✔️ Teste 001 — Opção inválida

- **Entrada:** 5  
- **Resultado esperado:**  
  Exibir mensagem de erro, pois as opções válidas são de 1 a 4.  

- **Resultado obtido:**  
  ✔️ Mensagem "Opção inválida" exibida corretamente.

---

## ❌ Teste 002 — Entrada de letras

- **Entrada:** abc  
- **Resultado esperado:**  
  O sistema deve exibir uma mensagem de erro sem travar.  

- **Resultado obtido:**  
  ❌ O sistema travou e não exibiu mensagem de erro.

---

## ⚠️ Teste 003 — Divisão por zero

- **Entrada:** opção 4, num1 = 10, num2 = 0  
- **Resultado esperado:**  
  Exibir mensagem de erro "divisão por zero" sem travar o sistema.  

- **Resultado obtido:**  
  ✔️ Mensagem exibida corretamente.

---

## ⚠️ Teste 004 — Números negativos

- **Entrada:** opção 1, num1 = -5, num2 = -3  
- **Resultado esperado:**  
  O sistema deve realizar o cálculo normalmente.  

- **Resultado obtido:**  
  ✔️ Funcionou corretamente.

---

## ⚠️ Teste 005 — Números decimais

- **Entrada:** opção 3, num1 = 2.5, num2 = 2  
- **Resultado esperado:**  
  O sistema deve calcular corretamente valores decimais.  

- **Resultado obtido:**  
  ✔️ Funcionou corretamente.

---

## 📌 Conclusão

O sistema apresenta falha na validação de entrada, pois não trata dados inválidos (como letras), causando travamento.

No geral, as operações matemáticas funcionam adequadamente.
