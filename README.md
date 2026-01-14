📊 Previsão de Estoque Inteligente com AWS SageMaker Canvas
Este projeto foi desenvolvido como parte de um desafio prático utilizando o Amazon SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (No-Code).

🎯 Objetivos do Projeto
O objetivo principal foi prever a demanda de estoque (QUANTIDADE_ESTOQUE) para os próximos dias, utilizando dados históricos de vendas, preços e promoções.

🛠️ Tecnologias Utilizadas
AWS SageMaker Canvas: Plataforma de Machine Learning sem código.

Amazon S3: Para armazenamento do dataset na nuvem (Região: Ohio - us-east-2).

Dataset CSV: Contendo informações de ID_PRODUTO, DATA_EVENTO, PRECO e QUANTIDADE_ESTOQUE.

📈 Resultados e Performance
O modelo foi treinado utilizando a opção Quick Build e apresentou as seguintes métricas de performance:

MAPE (Erro Médio Percentual Absoluto): 0.148 (O que indica uma precisão aproximada de 85.2%).

WAPE: 0.100.

RMSE: 5.765.

Essas métricas mostram que o modelo é capaz de prever com boa fidelidade as variações de estoque para os itens analisados.

🚀 Passo a Passo Realizado
Importação de Dados: Upload do dataset para o SageMaker Canvas.

Configuração do Modelo: Definição da coluna alvo (QUANTIDADE_ESTOQUE) e do identificador do item (ID_PRODUTO).

Treinamento: Execução do Quick Build para gerar as previsões.

Análise: Verificação das métricas de erro e do impacto de cada variável no estoque.

Previsão: Geração de gráficos de tendência para itens específicos através da aba Single Prediction.

🧹 Gestão de Recursos (FinOps)
Após a conclusão das análises e captura de evidências, todos os recursos foram devidamente encerrados para evitar custos desnecessários na conta AWS:

Log out realizado no SageMaker Canvas.

Modelos e Datasets deletados na região de Ohio (us-east-2).
