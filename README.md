🛒 Análise Exploratória de Dados de Vendas (EDA)

## 📝 Sobre o projeto

Este repositório reúne uma **Análise Exploratória de Dados (EDA)** feita em Python, com o propósito de entender como as vendas se comportam ao longo do tempo e transformar esses dados em insights que ajudem na tomada de decisão.

Todo o processo foi conduzido em um **Jupyter Notebook/Google Colab**, apoiado principalmente nas bibliotecas **Pandas, NumPy, Matplotlib e Seaborn**.

---

## 🚀 Objetivos

- Importar e explorar um conjunto de dados de vendas;
- Avaliar a qualidade e a consistência dos dados;
- Tratar e converter tipos de dados;
- Construir novas variáveis (Feature Engineering);
- Gerar análises estatísticas e visuais;
- Reconhecer padrões nas vendas;
- Propor recomendações a partir dos resultados obtidos.

---

## 🗂️ Dataset

O projeto utiliza o arquivo:

`sales_data.csv`

As principais colunas do conjunto de dados são:

- Date
- Region
- Product
- Sales
- Cost

---

## ⚙️ Tecnologias utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 🔍 Etapas da análise

O notebook segue este roteiro:

### 1. Preparação do ambiente
- Importação das bibliotecas
- Configuração do estilo visual (tema do Seaborn)

### 2. Carregamento dos dados
- Upload e leitura do arquivo CSV
- Checagem das colunas obrigatórias

### 3. Inspeção inicial
- Primeiras visualizações dos registros
- Tipos de dados
- Valores ausentes e linhas duplicadas
- Resumo estatístico

### 4. Ajuste dos tipos de dados
- Conversão da coluna `Date` para formato de data
- Reordenação cronológica das linhas

### 5. Engenharia de atributos
Novas colunas criadas a partir dos dados originais:
- `Month`
- `Day_of_Week`
- `Profit`
- `Margin_Percent`
- `Sales_Normalized`
- `Sales_Tier`

### 6. Análise exploratória
Cruzamentos e agrupamentos feitos ao longo do notebook:
- Vendas por região
- Custos
- Lucro
- Número de transações
- Vendas por dia da semana

### 7. Visualizações
Diferentes gráficos foram usados para tornar os padrões mais visíveis, entre eles:
- Histogramas
- Gráficos de dispersão
- Pairplot
- Gráficos de barras

### 8. Conclusões
O notebook fecha com a leitura dos resultados encontrados e recomendações de negócio baseadas nos padrões identificados — por exemplo, explorar melhor os dias de pico de vendas e criar ações para impulsionar os dias mais fracos.

---

## 🖥️ Como executar

1. Abra o notebook no Google Colab.
2. Execute as células em ordem (Shift + Enter).
3. Quando solicitado o upload, selecione o arquivo `sales_data.csv`.
4. Preencha a atividade proposta e registre suas conclusões.
5. Envie o notebook e o CSV para um repositório no GitHub.

---

## 💡 Aprendizados do projeto

- Estruturar uma EDA do início ao fim, desde a inspeção dos dados até a comunicação dos resultados;
- Entender por que checar valores ausentes, duplicados e tipos de dados vem antes de qualquer conclusão;
- Manipular datas com Pandas para extrair informações temporais, como mês e dia da semana;
- Criar novas variáveis (feature engineering) que agregam valor à análise, como lucro, margem e faixa de vendas;
- Usar `groupby` para responder perguntas de negócio de forma direta e objetiva;
- Escolher o gráfico certo para cada pergunta, alternando entre histograma, dispersão, pairplot e barras;
- Perceber que gráfico e número prontos não bastam — o valor está na interpretação e nas recomendações que eles geram;
- Praticar o fluxo de publicação de um projeto de dados no GitHub, do notebook à documentação.
