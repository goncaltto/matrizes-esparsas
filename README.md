<div align="center">

# 📊 MATRIZES ESPARSAS

Implementação e análise de desempenho de diferentes representações de matrizes esparsas.

</div>

---

## 📌 SOBRE O PROJETO

Este projeto implementa matrizes esparsas utilizando duas abordagens distintas, com o objetivo de analisar eficiência em termos de memória e tempo de execução.

Foram desenvolvidas duas representações:

- Matriz estática (array bidimensional)  
- Matriz utilizando listas encadeadas  

Matrizes esparsas possuem grande quantidade de valores zero, permitindo otimização ao armazenar apenas os elementos não nulos.

---

## 🎯 OBJETIVO

- Comparar diferentes estruturas de dados  
- Avaliar desempenho em operações com matrizes  
- Reduzir uso de memória  
- Aplicar conceitos de estruturas de dados na prática  

---

## ⚙️ FUNCIONALIDADES

As duas implementações incluem:

- Inserção de elementos  
- Remoção de elementos  
- Busca de valores  
- Impressão da matriz  

### 🔍 Verificações

- Matriz vazia  
- Matriz diagonal  
- Matriz linha  
- Matriz coluna  
- Matriz triangular (superior e inferior)  
- Matriz simétrica  

### ➕ Operações

- Soma de matrizes  
- Multiplicação de matrizes  
- Transposta  

---

## 🧠 ESTRUTURA DO PROJETO

O sistema é dividido em duas abordagens principais:

### 🔹 Matriz Estática

- Implementação com array bidimensional  
- Acesso direto aos elementos  
- Maior consumo de memória  

### 🔹 Listas Encadeadas

- Armazena apenas valores diferentes de zero  
- Estrutura baseada em nós  
- Formato: (linha, coluna, valor)  
- Mais eficiente para matrizes esparsas  

---

## 📈 TESTES DE DESEMPENHO

Foram realizados testes com matrizes de diferentes tamanhos:

- 60% de elementos nulos  
- Execução de cada operação 10 vezes  
- Cálculo de tempo médio  

---

## 📊 RESULTADOS

- Listas encadeadas são mais eficientes em memória  
- Matriz estática é mais simples de implementar  
- O desempenho varia conforme operação e tamanho da matriz  

---

## 🚀 COMO EXECUTAR

```bash
git clone https://github.com/goncaltto/matrizes-esparsas.git
```

## 🛠️ TECNOLOGIAS UTILIZADAS
 - Java
 - 
##📚 CONCEITOS ABORDADOS

- Matrizes esparsas
- Estruturas dinâmicas
- Complexidade de algoritmos
- Análise de desempenho
