📊 Matrizes Esparsas

Implementação de matrizes esparsas utilizando duas abordagens distintas, com o objetivo de analisar eficiência em termos de uso de memória e desempenho.

📌 Sobre o projeto

Este projeto foi desenvolvido como trabalho da disciplina de Estruturas de Dados, com foco na implementação e comparação de duas formas de representação de matrizes esparsas:

🔹 Representação estática (matriz tradicional)

🔹 Representação com listas encadeadas

Matrizes esparsas são estruturas que possuem grande quantidade de valores zero, sendo possível otimizar armazenamento e processamento ao armazenar apenas os elementos não nulos .

🎯 Objetivo

Implementar operações sobre matrizes esparsas

Comparar diferentes estruturas de dados

Avaliar desempenho computacional

Analisar consumo de memória

⚙️ Funcionalidades

Ambas as implementações possuem os seguintes métodos:

Inserção e remoção de elementos

Busca de valores

Impressão da matriz

Verificação de:

Matriz vazia

Matriz diagonal

Matriz linha e coluna

Matriz triangular (superior e inferior)

Matriz simétrica

Operações matemáticas:

Soma

Multiplicação

Transposta

🧠 Estrutura do projeto

O projeto é dividido em duas principais classes:

MatrizEstatica → Representação tradicional (array bidimensional)

MatrizEsparsaLista → Representação com listas encadeadas

Na abordagem com listas encadeadas:

Apenas elementos ≠ 0 são armazenados

Cada elemento segue o formato: (linha, coluna, valor)

📈 Testes de desempenho

Foram realizados testes com matrizes de diferentes tamanhos:

10x10 até 100.000x100.000

Grau de esparsidade: 60% de zeros

Cada operação foi executada 10 vezes

Foi calculado o tempo médio de execução

📊 Resultados

Os resultados mostram que:

A abordagem com listas encadeadas é mais eficiente em memória

A matriz estática pode ser mais simples, porém menos eficiente em cenários com muitos zeros

O desempenho varia conforme o tamanho da matriz e operação realizada

🚀 Como executar

Clone o repositório:

git clone https://github.com/goncaltto/matrizes-esparsas.git

Abra o projeto na sua IDE (IntelliJ, Eclipse, VS Code)

Execute a classe principal

🛠️ Tecnologias utilizadas

Java

Estruturas de Dados (Listas Encadeadas)

📚 Conceitos abordados

Matrizes esparsas

Estruturas dinâmicas

Complexidade de algoritmos

Análise de desempenho

👩‍💻 Autoria

Desenvolvido por Jonathan Gonçalves Brito

📌 Observações

Este projeto tem caráter acadêmico, com foco no aprendizado de estruturas de dados e análise de eficiência.
