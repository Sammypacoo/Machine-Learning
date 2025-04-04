# 📌 Perceptron: Fórmula e Step Function  

## 🔹 Cálculo da saída do Perceptron  
A fórmula matemática do **Perceptron** pode ser expressa como:  

\[
y = f(z) = f\left(\sum_{i=1}^{n} w_i x_i + b\right)
\]

Onde:  
- \( x_i \) são as entradas (features)  
- \( w_i \) são os pesos correspondentes  
- \( b \) é o bias (termo de ajuste)  
- \( z = \sum_{i=1}^{n} w_i x_i + b \) é a soma ponderada das entradas  
- \( f(z) \) é a **função de ativação**  

## 🔹 Função de Ativação (Step Function)  
A **Step Function** define a saída binária do Perceptron:  

\[
f(z) =
\begin{cases} 
1, & \text{se } z \geq 0 \\
0, & \text{se } z < 0
\end{cases}
\]

Essa função decide se um dado pertence a uma classe ou outra.  
Se os dados forem **linearmente separáveis**, o Perceptron pode classificá-los corretamente ajustando os pesos ao longo das iterações.  

---
💡 *O Perceptron foi o primeiro neurônio artificial e serviu de base para redes neurais mais avançadas!*
