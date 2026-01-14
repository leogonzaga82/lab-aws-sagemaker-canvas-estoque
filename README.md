📊 Previsão de Estoque Inteligente com AWS SageMaker Canvas
Este projeto foi desenvolvido para demonstrar o uso do Amazon SageMaker Canvas na criação de modelos de previsão de estoque sem a necessidade de escrever código (No-Code Machine Learning).

🎯 Objetivos
O objetivo foi prever a demanda futura (QUANTIDADE_ESTOQUE) baseada em dados históricos, ajudando na tomada de decisão para reposição de produtos.

🛠️ Tecnologias Utilizadas
AWS SageMaker Canvas: Para treinamento e análise do modelo preditivo.

Dataset: Arquivo CSV contendo histórico de vendas e preços.

GitHub: Para documentação e versionamento do projeto.

📈 Resultados do Modelo (Métricas)
O modelo foi treinado com sucesso e apresentou as seguintes métricas de performance na aba Analyze:

MAPE (Erro Médio Percentual Absoluto): 0.148 (Precisão de ~85%).

WAPE: 0.100.

RMSE: 5.765.

🚀 Passo a Passo Realizado
1. Preparação do Dataset
Os dados foram importados e configurados, identificando as colunas de ID do produto, data e o alvo da previsão.

2. Treinamento (Build)
Utilizamos a opção Quick Build para treinar o modelo de série temporal.

3. Previsões Individuais (Predict)
Na aba Predict, geramos previsões para itens específicos para visualizar a tendência futura de estoque.

🧹 Gestão de Recursos (FinOps)
Seguindo as boas práticas de gestão de nuvem, após a conclusão do projeto:

Os prints foram capturados para documentação.

O Log out foi realizado para encerrar a sessão do Canvas.

O modelo e o dataset foram removidos da conta AWS na região de Ohio (us-east-2) para evitar cobranças indesejadas.
