# pipeline-vendas-analytics
# Pipeline de Dados para Análise de Vendas

## OBJETIVO
Construir um pipeline de dados estruturado para análise de vendas de e-commerce, organizando os dados desde a ingestão até a camada analítica.

## ARQUITETURA
O projeto foi dividido em três camadas:

- **Staging:** limpeza e padronização dos dados brutos  
- **Intermediate:** aplicação de regras de negócio e enriquecimento  
- **Mart:** modelagem analítica (fato e dimensões)

## ESTRUTURA DO PROJETO
/sql  
  /staging  
  /intermediate  
  /marts  
/data  

## FERRAMENTAS
- SQL  
- PostgreSQL  
- Power BI  

## PIPELINE DE DADOS
1. Dados brutos carregados no banco  
2. Tratamento na camada staging  
3. Transformações e joins na intermediate  
4. Criação de tabelas analíticas (fat e dim)  
5. Consumo no Power BI  

## ANÁLISES
- Receita total  
- Receita por período  
- Ticket médio  
- Clientes recorrentes  

## RESULTADO
Criação de um modelo de dados estruturado para suportar análises de negócio e dashboards.
