# Análise de Churn em Assinaturas - Relatório e Código

## Introdução

Este projeto tem como objetivo analisar os dados fornecidos pela Petlove para entender os padrões e fatores-chave que influenciam o aumento no churn em assinaturas. A análise é realizada utilizando a linguagem Python e as bibliotecas pandas, matplotlib, seaborn, e scikit-learn.

## Aprendizados-chave da Análise de Dados

### 1. Exploração Geral dos Dados

- **Distribuições:** Foram analisadas as distribuições de variáveis importantes como `average_ticket`, `items_quantity`, `all_revenue`, `all_orders`, e `recency`. Isso proporcionou uma compreensão inicial da variação e amplitude dessas métricas.

- **Marketing Source:** Uma contagem da origem de marketing foi visualizada para entender as fontes predominantes de aquisição de clientes.

### 2. Análise de Churn

- **Taxa de Churn:** A taxa de churn foi calculada, indicando a proporção de clientes que pausaram as assinaturas em relação ao total de clientes ativos e pausados.

- **Agrupamento por Status:** As médias das métricas numéricas foram calculadas para clientes ativos e pausados. Isso permitiu a identificação de diferenças significativas entre esses grupos.

- **Taxa de Churn por Origem de Marketing:** Foi analisada a taxa de churn para cada origem de marketing, destacando fontes que apresentam taxas mais altas.

- **Correlação com Recência:** A correlação média entre a recência das compras e o status de churn foi explorada, fornecendo insights sobre a relação temporal das pausas.

### 3. Matriz de Correlação

- Uma matriz de correlação foi gerada para avaliar as relações lineares entre variáveis numéricas.

## Próximos Passos Sugeridos

Com base nos insights obtidos, algumas ações sugeridas para a equipe de negócios são:

1. **Aprimoramento da Experiência do Cliente:**
   - Investir em melhorias na experiência do cliente para aumentar a satisfação e engajamento, potencialmente reduzindo a taxa de churn.

2. **Análise Detalhada de Origens de Marketing:**
   - Realizar uma análise mais detalhada das origens de marketing com taxas de churn mais altas para entender os desafios específicos em cada canal.

3. **Incentivos e Benefícios:**
   - Introduzir programas de incentivo e benefícios para clientes mais antigos, visando aumentar a lealdade e reduzir o churn.

4. **Monitoramento Contínuo:**
   - Estabelecer um sistema de monitoramento contínuo para identificar tendências de churn em tempo real e permitir intervenções proativas.

5. **Pesquisa de Satisfação:**
   - Realizar pesquisas de satisfação para entender as necessidades e expectativas dos clientes, utilizando esses insights para melhorar os serviços.

## Estrutura do Código

O código está organizado em seções correspondentes às etapas da análise, facilitando a compreensão e replicação do processo. As visualizações são apresentadas de forma clara, auxiliando na interpretação dos resultados.

## Conclusão

Este projeto oferece uma visão aprofundada dos fatores que contribuem para o aumento no churn em assinaturas da Petlove. As sugestões fornecidas são baseadas em insights extraídos da análise de dados e destinam-se a orientar a equipe na implementação de estratégias eficazes para redução do churn. A abordagem transparente e documentada visa facilitar a colaboração e garantir a compreensão da análise realizada.


