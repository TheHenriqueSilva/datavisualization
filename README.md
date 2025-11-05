
# 📊 Data Visualization: Gráficos & Comparação de Dados

Este projeto faz parte de um portfólio de Data Visualization, focado na exploração e análise de duas bases de dados distintas, utilizando recursos visuais (gráficos e elementos visuais) para responder a questionamentos específicos levantados sobre os dados. A análise detalhada é apresentada no Jupyter Notebook: `Projeto+Final+-+Dataviz_+Gráficos.ipynb`.

## 🎯 Objetivo do Projeto

O objetivo principal é construir um portfólio de Data Visualization por meio da análise de duas bases de dados:

1.  Análise de dados de vendas de uma grande rede de lojas de departamentos que opera em todo o Brasil.
2.  Análise da distribuição de volumes e medidas de produtos de uma empresa de itens de limpeza.

## 📁 Bases de Dados

O projeto utiliza duas fontes de dados no formato CSV, acessíveis via link público, para demonstrar diferentes tipos de análise e visualização:

| Base de Dados | Descrição |
| :--- | :--- |
| **Vendas da Rede de Lojas** | Pedidos de clientes entre 2016 e 2019. |
| **Distribuição de Produtos (Limpeza)** | Amostras de volume de amaciante (1L) e medidas (altura, comprimento, largura) de caixas de sabão em pó (1000 amostras medidas cada). |

A base de dados de vendas é carregada no notebook a partir da seguinte URL: `https://raw.githubusercontent.com/afonsosr2/dataviz-graficos/master/dados/relatorio_vendas.csv`.

## 🔎 Análises Chave (Dados de Vendas)

A primeira parte do projeto foca em gráficos de colunas para comparar e agrupar dados de vendas, buscando responder a perguntas como:

1.  Qual o total de vendas por ano e qual ano teve o melhor desempenho?
2.  Qual é o top 7 de produtos com maior lucro?
3.  Qual a distribuição do total de vendas por ano e por regiões?
4.  Qual o modo de envio mais utilizado pelos clientes e se a proporção é a mesma para os segmentos B2B e B2C?
5.  Qual o total de vendas por trimestre no estado de São Paulo?
6.  Qual o faturamento por trimestre em cada região?

## 🎨 Paleta de Cores

Uma paleta de cores específica foi definida no projeto para garantir a consistência visual nos gráficos gerados:

| Cor | Nome | Hex Code |
| :--- | :--- | :--- |
|  | AZUL1 | `#03045e` |
|  | AZUL2 | `#0077b6` |
|  | AZUL3 | `#00b4d8` |
|  | AZUL4 | `#90e0ef` |
|  | AZUL5 | `#CDDBF3` |
|  | CINZA1 | `#212529` |
|  | CINZA2 | `#495057` |
|  | VERMELHO1 | `#e76f51` |
|  | LARANJA1 | `#f4a261` |
|  | AMARELO1 | `#e9c46a` |

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em um ambiente de Jupyter Notebook e utiliza as seguintes bibliotecas Python:

  * **Pandas:** Para manipulação e tratamento dos dados.
  * **Matplotlib:** Para a geração e personalização dos gráficos.

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github
    ```
2.  **Instale as dependências:**
    ```bash
    pip install pandas matplotlib
    ```
3.  **Abra o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Execute o arquivo `Projeto+Final+-+Dataviz_+Gráficos.ipynb`** e siga as células de código para replicar as análises e visualizações.
