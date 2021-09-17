# Desafio-PowerBI-Semana1


## Dashboard de Logística
  Foi proposto a elaboração de um relatório para verificar as demandas da AluraShop nos últimos 3 anos analisando algumas métricas.


## Base de dados
  Foram utilizados 4 arquivos .csv com as seguintes características:

Tabela de pedidos
  - Data do pedido
  - Data de entrega
  - Data previsão entrega
  - ID pedido
  - Latitude
  - Longitude
  - UF da entrega
  - ID Produto
  - Quantidade
  - ID veículo  


Tabela Produtos
  - ID Produto
  - Categoria Produto
  - Valor
 
 
Tabela Estoque
  - Data atualização
  - Quantidade
  - ID Produto


ID veículo
  - Tipo
  - Status


## Ferramentas utilizadas para o projeto
  Foi utilizado o Power BI desde a realização do tratamento de dados até a construção do Dashboard.
  
## Tratamento de dados

Tabela pedidos
  - Alteração na tipagem dos dados, colocado a tipagem correta
  - Tratamento lógico para pedidos que ainda estão em trânsito


Tabela estoque
  - Alteração na tipagem dos dados, colocado a tipagem correta
 
 
Tabela produtos
  - Alteração na tipagem dos dados, colocado a tipagem correta
  - Separar o ID do produto da categoria dele
  - Substituir underscore por espaço
  - Deixar a primeira letra de cada palavra em maíusculo


Tabela veículos
  - Alteração na tipagem dos dados, colocado a tipagem correta
  - Extrair o ID dos veículos removendo o prefixo VEH


## Métricas utilizadas
  - Entregas no prazo
  - Entregas atrasadas
  - Veículos disponíveis para entrega
  - S2D - Ship to door
  - Índice de ocorrências por estado
  - Média do estoque no decorrer do tempo

## Relacionamentos
  -  Pedidos(n) - (1)Produtos = muitos para 1 (n - 1)
  -  Pedidos(n) - (1)Veículos = muitos para 1 (n - 1)
  -  Estoque(n) - (1)Produtos = muitos para 1 (n - 1)
