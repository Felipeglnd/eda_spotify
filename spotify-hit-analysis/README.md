# 🎧 Spotify Data EDA: Desvendando os Motores do Sucesso

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

Este projeto apresenta uma Análise Exploratória de Dados (EDA) completa sobre o dataset de músicas mais ouvidas do Spotify. O objetivo foi identificar padrões que separam os hits globais das demais faixas, utilizando técnicas estatísticas e visualizações avançadas.

## 🎯 Objetivos do Projeto
* Identificar a concentração de mercado.
* Analisar a correlação entre características musicais e popularidade.
* Avaliar o impacto da curadoria (playlists) no volume de streams.
* Estudar a sazonalidade e idade dos lançamentos.

## 📊 Principais Insights

### 1. Análise de Pareto (Concentração)
Diferente da regra clássica de 80/20, identificamos que no streaming a proporção é de **80/34**. São necessários 221 artistas para compor 80% do volume total de streams, indicando uma "classe média" de artistas relevante no ecossistema.

### 2. O "Mito" da Fórmula Musical
Através do Mapa de Correlação de Spearman, provamos que atributos como BPM, Energia e Dançabilidade não explicam o sucesso de uma música isoladamente. O verdadeiro driver de performance é a **presença em playlists**, com correlação de **0.83**.

### 3. Sazonalidade e Perfil
A maioria dos hits atuais pertence à categoria de lançamentos "Recentes", mostrando a velocidade de renovação do catálogo da plataforma.

## 🛠️ Tecnologias Utilizadas
* **Python** para processamento de dados.
* **Pandas** para manipulação de dataframes.
* **Seaborn/Matplotlib** para visualizações complexas e gráficos de Pareto.
* **NumPy** para operações matemáticas.

## 📂 Estrutura do Repositório
* `notebooks/`: Contém o arquivo .ipynb com o código completo.
* `data/`: Dataset utilizado (ou link para a fonte original).
* `images/`: Gráficos gerados durante a análise.

## 👨‍💻 Autor
Felipe Galindo de Freitas Lima
- LinkedIn: https://www.linkedin.com/in/felipe-galindo123/
