# 🧠 Tecnologia e Saúde Mental

Projeto de análise exploratória de dados e visualização sobre a relação entre tecnologia, ambiente de trabalho e saúde mental.

O projeto foi desenvolvido como parte da formação em Ciência de Dados na Universidade Federal do Ceará (UFC), com o objetivo de explorar os dados de uma pesquisa sobre saúde mental no ambiente de trabalho e transformar os resultados em visualizações interativas.

## 📊 Dashboard

O projeto conta com um dashboard interativo desenvolvido em Streamlit, permitindo explorar os dados por diferentes filtros e visualizar informações relacionadas à saúde mental no ambiente profissional.

🔗 "Acessar o Dashboard" (https://saude-tecnologia-ufc.streamlit.app/)

O dashboard permite filtrar os dados por:

- 🌎 País
- 🎂 Faixa etária

A partir dos filtros selecionados, as visualizações e métricas são atualizadas dinamicamente.

---

## 🎯 Objetivo

O objetivo do projeto é utilizar técnicas de análise e visualização de dados para investigar diferentes aspectos relacionados à saúde mental no ambiente de trabalho, facilitando a interpretação das informações por meio de gráficos e indicadores.

Entre os aspectos explorados estão:

- Busca por tratamento de saúde mental;
- Relação entre gênero e busca por tratamento;
- Interferência da saúde mental no trabalho;
- Consequências percebidas ao discutir saúde mental;
- Relação entre saúde mental e saúde física;
- Características demográficas dos participantes.

---

## 🔎 Análises realizadas

O projeto apresenta diferentes análises exploratórias dos dados.

Busca por tratamento por gênero

Análise da quantidade de participantes que buscaram ou não tratamento de saúde mental, segmentada por gênero.

Interferência da saúde mental no trabalho

Visualização da frequência das diferentes respostas relacionadas à interferência da saúde mental no ambiente profissional.

Consequências de discutir saúde mental

Análise das respostas relacionadas às possíveis consequências percebidas ao discutir questões de saúde mental no ambiente de trabalho.

Saúde mental vs. saúde física

Visualização da percepção dos participantes sobre sua saúde mental em comparação com sua saúde física.

Estatísticas descritivas

Também são apresentadas estatísticas descritivas de variáveis selecionadas, incluindo:

- Idade;
- Gênero;
- País;
- Busca por tratamento;
- Histórico familiar;
- Interferência no trabalho.

---

## 🛠️ Tecnologias utilizadas

Linguagem

- Python

Análise e tratamento de dados

- Pandas

Visualização de dados

- Plotly Express
- Plotly Graph Objects

Dashboard

- Streamlit

Desenvolvimento e versionamento

- Jupyter Notebook
- Git
- GitHub

---

## 📁 Estrutura do projeto

Tecnologias-e-sa-de-de-mental/
│
├── TrabalhoFinal_LAB_C_D_.ipynb   # Notebook com a análise do projeto
├── dashboard.py                   # Aplicação do dashboard\\
├── dados_corrigidos (1).csv       # Base de dados utilizada no dashboard\\
├── survey.csv                     # Dados da pesquisa\\
└── README.md                      # Documentação do projeto\\

---

## 🚀 Como executar o projeto

1. Clone o repositório

git clone https://github.com/Davyeeh/Tecnologias-e-sa-de-de-mental.git

2. Acesse a pasta

cd Tecnologias-e-sa-de-de-mental

3. Instale as dependências

pip install streamlit pandas plotly

4. Execute o dashboard

streamlit run dashboard.py

O Streamlit iniciará o dashboard localmente no navegador.

---

## 📚 Contexto acadêmico

Projeto desenvolvido no contexto da formação em Ciência de Dados na Universidade Federal do Ceará (UFC).

O trabalho envolve etapas de exploração e visualização de dados, utilizando Python para transformar dados de pesquisa em informações que possam ser analisadas de maneira mais clara e interativa.

---

## 🌐 Projeto online

Dashboard:
https://saude-tecnologia-ufc.streamlit.app/

Repositório:
https://github.com/Davyeeh/Tecnologias-e-sa-de-de-mental