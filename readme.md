# Teste Técnico - Programa Trainee triggo.ai de Excelência em Engenharia de Dados e DataOps 2025

## Introdução

Chegou a hora de dar o próximo passo rumo à sua jornada no Bootcamp - Programa Trainee triggo.ai de Excelência em Engenharia de Dados e DataOps!
Você foi selecionado para realizar o Teste Técnico, a etapa que vai colocar à prova suas habilidades técnicas (Python, SQL, Banco de Dados e lógica de programação)  em um ambiente que simula desafios reais da área de Dados. Mostre do que é capaz e destaque-se entre os melhores talentos do Brasil!
 
🔍 Prepare-se, concentre-se e dê o seu melhor.
Essa é a sua chance de mostrar por que você tem tudo para ser protagonista na transformação digital com a triggo.ai!

## Objetivo

Você foi contratado como Engenheiro de Dados Junior para uma empresa de e-commerce brasileira. Sua primeira tarefa é analisar o conjunto de dados históricos de vendas para extrair insights valiosos que possam ajudar nas decisões estratégicas do negócio.

## Dataset

Para este teste, você utilizará o "Brazilian E-commerce Public Dataset by Olist" disponível no Kaggle. Este dataset contém informações sobre 100.000 pedidos de e-commerce no Brasil realizados entre 2016 e 2018.

Link para o dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Instruções

1. Faça o download do dataset do Kaggle
2. Crie um notebook no Google Colab
3. Desenvolva o código necessário para responder às questões abaixo
4. Crie um repositório no GitHub e faça o upload do notebook desenvolvido
5. Certifique-se de documentar adequadamente seu código
6. O notebook deve conter todas as análises, visualizações e conclusões solicitadas

## Requisitos Técnicos

- Uso de Python (pandas, numpy, matplotlib, seaborn)
- Uso de SQL (pode ser por meio do SQLite ou pandas)
- Criação de visualizações e dashboards interativos (pode usar plotly, matplotlib, seaborn)
- Aplicação de boas práticas de código

## Tarefas

### 1. Preparação dos Dados (25 pontos)

- Importar os arquivos CSV do dataset
- Realizar a limpeza necessária (tratar valores nulos, remover duplicatas, etc.)
- Fazer a normalização de colunas quando necessário
- Criar um modelo relacional e conectar as tabelas adequadamente
- Descrever os passos de preparação dos dados adotados

### 2. Análise Exploratória de Dados (25 pontos)

- Responda às seguintes perguntas utilizando SQL e Python:
   
   a) Qual o volume de pedidos por mês? Existe sazonalidade nas vendas?
   
   b) Qual a distribuição do tempo de entrega dos pedidos? 
   
   c) Qual a relação entre o valor do frete e a distância de entrega?
   
   d) Quais são as categorias de produtos mais vendidas em termos de faturamento?
   
   e) Quais estados brasileiros possuem o maior valor médio de pedido?

### 3. Solução de Problemas de Negócio (25 pontos)

Você deve resolver as seguintes questões de negócio:

1. **Análise de Retenção**: Calcule a taxa de clientes recorrentes. Considere um cliente recorrente aquele que fez mais de um pedido no período analisado. Quais insights podemos extrair destes dados?

2. **Predição de Atraso**: Crie um modelo simples para prever se um pedido será entregue com atraso. 
   - Defina o que seria um pedido atrasado (baseado nas colunas disponíveis)
   - Use os campos relevantes para criar features para seu modelo
   - Divida o dataset em treino e teste
   - Implemente um modelo de classificação simples (pode usar Regressão Logística, Random Forest ou outro de sua escolha)
   - Avalie a performance do modelo e explique os resultados

3. **Segmentação de Clientes**: Utilize técnicas de clustering para segmentar os clientes em grupos. Analise o comportamento de cada grupo e sugira estratégias de marketing específicas para cada um.

4. **Análise de Satisfação**: Explore a relação entre a nota de avaliação dos clientes e diferentes aspectos como categoria do produto, tempo de entrega, valor do pedido, etc. Identifique fatores que mais impactam na satisfação do cliente.

### 4. Visualização e Dashboards (25 pontos)

Crie visualizações e dashboards que respondam às seguintes necessidades:

1. Um dashboard geral que mostre a evolução das vendas ao longo do tempo, com filtros por estado e categoria de produto

2. Um mapa de calor mostrando a concentração de vendas por região/estado do Brasil

3. Um conjunto de gráficos que apresente a relação entre avaliação do cliente e tempo de entrega

4. Um dashboard de análise dos vendedores, mostrando quais têm melhor desempenho em termos de volume de vendas, satisfação do cliente e tempo de entrega

## Critérios de Avaliação

Você será avaliado com base nos seguintes critérios:

- **Qualidade do código**: legibilidade, organização, documentação
- **Conhecimento técnico**: domínio de Python, SQL e ferramentas de análise de dados
- **Habilidade analítica**: capacidade de extrair insights relevantes dos dados
- **Resolução de problemas**: abordagem utilizada para resolver os problemas propostos
- **Visualização de dados**: clareza e relevância das visualizações criadas
- **Comunicação**: capacidade de explicar os resultados de forma clara e concisa

## Entrega

1. Envie o link do seu repositório GitHub contendo:
   - O notebook Jupyter/Google Colab com todo o código desenvolvido
   - Um README.md explicando como executar o projeto e os principais resultados encontrados
   - Qualquer arquivo adicional que julgar necessário

2. Prazo de entrega: 7 dias a partir do recebimento do teste

## Dicas

- Documente seu raciocínio ao longo do notebook
- Priorize a qualidade da análise em vez da quantidade
- Não se esqueça de explicar suas decisões técnicas
- Seja criativo nas visualizações, mas mantenha o foco na clareza da informação
- Tenha cuidado com a performance do código, especialmente ao lidar com SQL

Boa sorte! Estamos ansiosos para ver sua solução.
