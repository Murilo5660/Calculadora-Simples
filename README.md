# Calculadora em Python (Simples e Avançada)

Este projeto consiste no desenvolvimento de uma **calculadora em Python**, capaz de realizar operações matemáticas básicas e avançadas **sem o uso de bibliotecas externas**.
O objetivo foi aplicar conceitos de entrada de dados, condicionais, tratamento de erros e lógica de programação.

---

## Funcionalidades

A calculadora permite realizar as seguintes operações:

### ✔ Operações Obrigatórias

* Soma
* Subtração
* Multiplicação
* Divisão
* Potenciação

### ✔ Tratamento de Erros

* **Divisão por zero:** o programa avisa o usuário que a operação não é possível.
* **Potenciação com expoente 0:** retorna automaticamente o valor **1**, conforme a regra matemática.

---

## Como usar

1. O programa solicita dois números ao usuário.
2. Em seguida, exibe um menu com as operações disponíveis.
3. O usuário escolhe uma operação digitando um número de 1 a 5.
4. O resultado é exibido com tratamento de erros quando necessário.

---

## 📄 Código Completo

```python
# ---------------------------------------------
# CALCULADORA SIMPLES E AVANÇADA EM PYTHON
# Sem uso de bibliotecas
# ---------------------------------------------

# Entrada de dados: pedir ao usuário 2 números
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

# Menu de operações
print("\nQual operação deseja realizar?")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")
print("5 - Potenciação")

op = input("Escolha a operação (1-5): ")

# Processamento das operações
print("\n--- RESULTADO ---")

if op == "1":
    resultado = num1 + num2
    print("Resultado da soma:", resultado)

elif op == "2":
    resultado = num1 - num2
    print("Resultado da subtração:", resultado)

elif op == "3":
    resultado = num1 * num2
    print("Resultado da multiplicação:", resultado)

elif op == "4":
    if num2 == 0:
        print("Erro: não é possível dividir por zero!")
    else:
        resultado = num1 / num2
        print("Resultado da divisão:", resultado)

elif op == "5":
    if num2 == 0:
        print("Resultado da potenciação:", 1)
    else:
        resultado = num1 ** num2
        print("Resultado da potenciação:", resultado)

else:
    print("Opção inválida! Escolha um número entre 1 e 5.")
```

---

## 📝 Relatório Final

### 📌 O que foi entregue *(com datas sugeridas)*

* Estrutura básica do programa
* Implementação das operações matemáticas
* Tratamento de erros e regras especiais
* Comentários internos e finalização geral
* Documentação e README

### 📌 Dificuldades encontradas

* Nenuma, pois ja havia feito projetos como esse

### 📌 Possíveis melhorias

* Criar um menu que permita repetir operações sem reiniciar o programa.
* Implementar novas funções matemáticas (raiz quadrada, porcentagem, módulo).
* Converter o código para funções (`def`).
* Criar uma interface gráfica usando Tkinter.
* Exportar histórico de cálculos.

---


## Autor
* Murilo 
* Projeto desenvolvido para fins educacionais, focado no aprendizado de lógica e programação básica em Python.

---
