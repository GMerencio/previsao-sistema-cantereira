# previsao-sistema-cantareira
Projeto referente à disciplina PJI410 - Projeto Integrador em Computação IV da Univesp que visa desenvolver modelos de previsão do volume do Sistema Cantareira utilizando métodos de machine learning e ferramentas de visualização de dados.

[A aplicação pode ser acessada aqui](https://previsao-cantareira.streamlit.app/).

## Tecnologias

As principais tecnologias usadas no projeto são:

* [Python 3.8](https://www.python.org/)
* [Prophet](https://facebook.github.io/prophet/)
* [Plotly](https://plotly.com/)
* [Streamlit](https://streamlit.io/)

## Estrutura do projeto

Os principais arquivos e diretórios são:

* `streamlit-app.py`: Arquivo de entrada da aplicação Streamlit responsável pela interface de visualização.
* `plotting_utils.py`: Funções de auxílio para as visualizações de dados.
* `SABESP-sistemas_produtores.xlsx`: Série histórica contendo os dados dos reservatórios Jaguari-Jacareí, Cachoeira, Atibainha e Paiva Castro.
* `PI_IV.ipynb`: Notebook Jupyter com análise exploratória e tratamento dos dados.
* `modelo-prophet`: Diretório contendo o modelo que utiliza o Prophet para prever valores futuros.

## Setup 

 1. Instale [`pipenv`](https://pypi.org/project/pipenv/).
 2. No diretório do projeto, execute `pipenv install` no terminal.
 3. Para ativar o ambiente virtual, execute `pipenv shell`.
 4. Para rodar a aplicação Streamlit localmente, execute `streamlit run streamlit-app.py` no terminal. Lembre de ativar o ambiente virtual antes.