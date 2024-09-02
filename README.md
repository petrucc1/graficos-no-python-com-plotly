# Gráficos no Python com Plotly

Este notebook demonstra como criar gráficos interativos usando a biblioteca Plotly em Python. O exemplo a seguir mostra como criar um gráfico de linha simples.

## Estrutura do Projeto

- `main.ipynb`: Notebook principal contendo o código para gerar gráficos com Plotly.
- `tarefas.xlsx`: Arquivo Excel com dados que podem ser utilizados no notebook.

## Requisitos

- Python 3.12.5
- Plotly
- Pandas
- nbformat >= 4.2.0
- Extensão do Jupyter Notebook no VSCode

## Instalação

Para instalar as dependências necessárias, execute:

`pip install plotly pandas nbformat jupyter`

## Uso

1. Abra o arquivo main.ipynb em um ambiente Jupyter Notebook ou JupyterLab.
2. Execute as células para gerar gráficos interativos.
3. Personalize os gráficos conforme necessário.

## Exemplo de Código

O código a seguir importa a biblioteca Plotly e cria um gráfico de linha:

```python
# Importando Plotly e criando um gráfico
import plotly.express as px

dados_x = ["2018", "2019", "2020", "2021"]
dados_y = [23, 56, 12, 95]

fig = px.line(x = dados_x, y = dados_y, title = "Vendas X Ano", width = 600, height = 300, line_shape = "spline")
fig.show()
```

## Visualização

Para visualizar o gráfico, abra o arquivo `main.ipynb` em um ambiente Jupyter Notebook ou JupyterLab e execute as células de código. O gráfico interativo será exibido diretamente no notebook.

