# Repositório da Monografia

Bem-vindo ao repositório da minha monografia, intitulada "PREVISÃO DE INFLAÇÃO NO BRASIL: ANALISANDO A EFICÁCIA DE MODELOS DE MACHINE LEARNING". Este repositório contém os dados e scripts em Python utilizados para previsão do IPCA (Índice de Preços ao Consumidor Amplo) no âmbito da pesquisa apresentada. O objetivo é disponibilizar à banca corretora todos os recursos necessários para reproduzir os resultados e compreender a metodologia aplicada.

## Estrutura do Repositório

- **`data/`**: Contém o arquivo `Dados_TCC_2014_2024_Normalizados_TabUnica.xlsx` com dados normalizados do IPCA e variáveis preditoras, de 2014 a 2024.
- **`scripts/`**: Contém o script principal `main.ipynb` (ou outro nome que você definir) para carregamento, processamento, feature selection, treinamento de modelos e avaliação.
- **`requirements.txt`**: Lista de dependências Python necessárias para executar os scripts.

## Como Utilizar

1. **Pré-requisitos**:
   - Python 3.8+ instalado.
   - Bibliotecas listadas em `requirements.txt`. Para instalá-las, execute:
     ```bash
     pip install -r requirements.txt
2. **Execução do Script**:
   - Navegue até a pasta scripts/ e execute o script principal
   - O script realiza:
      Carregamento e pré-processamento dos dados.
      Feature selection usando Decision Tree.
      Treinamento de modelos (Linear Regression, SVR, Decision Tree, Gradient Boosting, Random Forest) com otimização de hiperparâmetros.
      Avaliação com métricas RMSE, MAE, MAPE e R².    
