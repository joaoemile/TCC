# Repositório da Monografia

Bem-vindo ao repositório da minha monografia, intitulada "PREVISÃO DE INFLAÇÃO NO BRASIL: ANALISANDO A EFICÁCIA DE MODELOS DE MACHINE LEARNING". Este repositório contém os dados e scripts em Python utilizados ao longo da fabricação do trabalho (seja para aprendizado, testes e tentativas anteriores) que tem como objetivo a previsão do IPCA (Índice de Preços ao Consumidor Amplo) no âmbito da pesquisa apresentada. O objetivo é disponibilizar corretora todos os recursos necessários para reproduzir os resultados e compreender a metodologia aplicada.

Os arquivos finais, utilizados efetivamente na versão final do trabalho, são: `Dados_TCC_2014_2024_Normalizados_TabUnica.xlsx` e `main.ipynb`

## Estrutura do Repositório

- **`data/`**: Contem arquivos de bases de dados, sendo o arquivo `Dados_TCC_2014_2024_Normalizados_TabUnica.xlsx` com o conjunto de dados utilizados no projeto unidos em uma única tabela, normalizados entre 0 e 1 e com defasagens dos ultimos 12 meses adicionados para cada variável.
- **`scripts/`**: Contém scripts feitos ao longo da pesquisa, sendo maior parte para aprendizado, testes e tentativas anteriores, utilizando outra base de dados que veio a ser trocada (maior parte usava a variável alvo como o IPCA acumulado). O script `main.ipynb` foi o efetivamente utilizado para carregamento, processamento, feature selection, treinamento de modelos e avaliação.
- **`arquivos/`**: Trata-se de arquivos gerados por mim para servir como base para imagens e tabelas de fabricação própria para a pesquisa, sendo algumas não utilizadas ou alteradas posteiormente.
- **`requirements.txt`**: Lista de dependências Python necessárias para executar os scripts.

## Como Utilizar

1. **Pré-requisitos**:
   - Python 3.8+ instalado.
   - Bibliotecas listadas em `requirements.txt`.
   - Jupyter Notebook ou JupyterLab para executar o arquivo.

2. **Execução do Script**:
   - Navegue até a pasta scripts/ e execute o script principal
   - O script realiza:
      Carregamento e pré-processamento dos dados.
      Feature selection usando Decision Tree.
      Treinamento de modelos (Linear Regression, SVR, Decision Tree, Gradient Boosting, Random Forest) com otimização de hiperparâmetros.
      Avaliação com métricas RMSE, MAE, MAPE e R².    
