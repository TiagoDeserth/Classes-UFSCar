# 📊 Análise de Aparecimento de Classes em Datasets Não-Estacionários

Este repositório contém um código em Python, para detectar o momento em que classes de um determinado conjunto de dados surgem. A análise é especialmente útil para datasets não-estacionários, onde a distribuição dos dados muda ao longo do tempo. 

## 📄 Datasets

Todos os datasets utilizados neste projeto são de origem de repositório CIG-UFSCar. O notebook exemplifica a análise com os seguintes datasets sintéticos não-estacionários.

## ⚙️ Funcionalidades

O código principal está na função `dataset_analysis()` que realiza as seguintes tarefas:

- 1. Carregamento de Dados: Carrega um dataset a partir de uma URL (arquivo CSV);
- 2. Visualizações:
-  - 📊 Cria um histograma para visualizar a distribuição das classes;
-  - 🎨 Gera um gráfico de dispersão para mostrar a distribuição dos dados por classes no espaço de atributos.
- 3. Detecção de Ocorrências:
-  - ✔️ Identifica e imprime a primeira ocorrência de cada classe no dataset;
-  - 📈 Plota um gráfico de linha que mostra a ocorrência das classes ao longo das instâncias, com marcações especiais indicando o surgimento de novas classes.

---

## 📚 Bibliotecas Utilizadas

Para executar este notebook, você precisará ter as seguintes bibliotecas Python instaladas:

- pandas: Para manipulação e análise de dados;
- seaborn: Para visualização de dados estatísticos;
- matplotlib.pyplot: Para a criação de gráficos e visualizações.

