# Telecom X - Análise de Evasão de Clientes (Churn) - Challenger de Ciência de Dados - Alura e One

## Descrição do Projeto

Este projeto consiste na análise exploratória de dados de clientes de uma empresa de telecomunicações para identificar padrões e fatores que influenciam a evasão (churn) dos clientes. A evasão representa um desafio importante para as empresas, pois impacta diretamente a receita e a sustentabilidade do negócio.

A partir dos dados disponíveis, o objetivo principal foi:

- Entender o perfil dos clientes que cancelam o serviço.
- Identificar variáveis associadas à maior probabilidade de churn.
- Gerar insights para estratégias de retenção de clientes.

## Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Estrutura do Projeto

- `TelecomX_Data.json`: arquivos de dados do projeto.
- `TelecomX_BR.ipynb`: Notebook com toda a análise, limpeza, visualizações e conclusões.

## Passos Realizados

1. **Importação e exploração inicial dos dados**  
   Avaliação da qualidade, tipos de dados e estrutura do dataset.

2. **Limpeza e tratamento dos dados**  
   Correção de valores ausentes, extração de dados aninhados, padronização de variáveis e criação de colunas adicionais, como gasto diário.

3. **Análise exploratória de dados (EDA)**  
   Visualizações para entender a distribuição do churn e sua relação com variáveis categóricas (gênero, contrato, método de pagamento) e numéricas (tempo de contrato, gasto total).

4. **Insights e recomendações**  
   Sugestões para reduzir a evasão com base nos resultados encontrados.

## Resultados Principais

- Clientes com contratos mensais e menor tempo de permanência apresentam maior risco de churn.
- O método de pagamento por boleto está associado a maior taxa de cancelamento.
- Clientes com menor gasto total tendem a cancelar mais.

## Como Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Larymattos/Challenger-Data-Science-TelecomX

2. Execute o notebook 'TelecomX_BR.ipynb' para visualizar a análise completa.
   
3. Bibliotecas utilizadas:
 - pandas
 - numpy
 - matplotlib
 - seaborn

📊 Projeto desenvolvido com foco em análise de dados e ciência de dados para suporte a decisões empresariais.

