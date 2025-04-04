# Perceptron - Implementação em Python

## 📌 Visão Geral
O Perceptron é um dos primeiros modelos de redes neurais artificiais, desenvolvido por Frank Rosenblatt em 1958. Ele é um classificador linear binário, ou seja, funciona bem quando os dados são linearmente separáveis.

Este repositório contém uma implementação simples do Perceptron em Python, utilizando NumPy para operações matemáticas.

## 📖 Como Funciona?
O Perceptron funciona combinando entradas ponderadas e passando o resultado por uma função de ativação chamada **Step Function**:

\[ y = f(\sum w_i x_i + b) \]

Onde:
- \( x_i \) são as entradas,
- \( w_i \) são os pesos associados a cada entrada,
- \( b \) é o bias,
- \( f(x) \) é a função de ativação (Step Function):
  
  \[ f(x) = \begin{cases} 
  1, & \text{se } x \geq 0 \\
  0, & \text{se } x < 0 
  \end{cases} \]

O modelo ajusta os pesos utilizando a regra de aprendizado:

\[ w_i = w_i + \eta (y_{real} - y_{previsto}) x_i \]

Onde \( \eta \) é a taxa de aprendizado.
