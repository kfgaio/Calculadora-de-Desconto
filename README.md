# Calculadora de Desconto

Este repositório contém um script simples em Python que calcula o valor final de uma compra, aplicando um desconto de 15% caso o valor da compra seja maior que R$ 100,00.

## 📋 Funcionalidades

- Solicita ao usuário o valor da compra.
- Aplica um desconto de 15% se o valor da compra for maior que R$ 100,00.
- Exibe o valor final a ser pago.

## 🚀 Como Usar

1. Certifique-se de ter o Python instalado na sua máquina.
2. Clone este repositório ou copie o código abaixo para um arquivo Python (`desconto.py`):

   ```python
   valor_compra = float(input("Digite o valor da compra: R$"))

   # Caso o valor seja maior que R$ 100, aplicar 15% de desconto
   if valor_compra > 100:
       valor_final = valor_compra * 0.85  
   else:
       valor_final = valor_compra  

   print(f"Valor final a ser pago: R${valor_final:.2f}")
