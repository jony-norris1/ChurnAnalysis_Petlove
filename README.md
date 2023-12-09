# Análise de Churn em Assinaturas - Relatório e Código

## Introdução

Este projeto foi realizado por João Paula e visa oferecer insights sobre o aumento no churn em assinaturas da Petlove por meio de uma análise detalhada dos dados. Utilizando Python e bibliotecas como pandas, matplotlib, seaborn e scikit-learn, exploramos o arquivo `data-test-analytics_5.csv`. É essencial ter esse arquivo para a execução da análise.

## Aprendizados-chave da Análise de Dados

### 1. Exploração Geral dos Dados

- **Distribuições:** Analisamos as distribuições de métricas cruciais, como `average_ticket`, `items_quantity`, `all_revenue`, `all_orders`, e `recency`. Destacamos a variabilidade em `recency`, indicando comportamentos distintos ao longo do tempo.

- **Marketing Source:** Realizamos uma contagem da origem de marketing para identificar as fontes predominantes de aquisição de clientes, fornecendo insights sobre estratégias de aquisição.

### 2. Análise de Churn

- **Taxa de Churn:** Calculamos a taxa de churn, revelando uma parcela significativa de clientes que pausam as assinaturas. Essa descoberta destaca a necessidade de compreender os motivos subjacentes a essas pausas.

- **Agrupamento por Status:** Calculamos as médias de métricas numéricas para clientes ativos e pausados, destacando disparidades notáveis. Isso sugere que clientes pausados podem apresentar comportamentos distintos.

- **Taxa de Churn por Origem de Marketing:** Identificamos origens de marketing com taxas de churn mais altas, indicando a necessidade de uma análise mais aprofundada para entender possíveis problemas nessas fontes.

- **Correlação com Recência:** Exploramos a correlação média entre recência e status de churn, indicando que clientes que pausam assinaturas tendem a ter uma recência diferente em comparação com clientes ativos.

### 3. Matriz de Correlação

- Geramos uma matriz de correlação para destacar relações lineares entre variáveis numéricas. A correlação entre `average_ticket` e `all_revenue` sugere uma possível relação proporcional.

## Próximos Passos Sugeridos

Com base nos insights obtidos, sugerimos as seguintes ações para a equipe de negócios:

1. **Aprimoramento da Experiência do Cliente:**
   - Investir em melhorias na experiência do cliente, especialmente em áreas identificadas com maior churn, para aumentar a satisfação e engajamento.

2. **Análise Detalhada de Origens de Marketing:**
   - Realizar uma análise mais detalhada das origens de marketing com taxas de churn mais altas para entender os desafios específicos em cada canal e otimizar estratégias de aquisição.

3. **Incentivos e Benefícios:**
   - Introduzir programas de incentivo e benefícios direcionados a clientes mais antigos, visando aumentar a lealdade e reduzir o churn.

4. **Monitoramento Contínuo:**
   - Estabelecer um sistema de monitoramento contínuo para identificar tendências de churn em tempo real e permitir intervenções proativas, especialmente em períodos críticos.

5. **Pesquisa de Satisfação:**
   - Realizar pesquisas de satisfação para entender as necessidades e expectativas dos clientes, utilizando esses insights para melhorar os serviços de acordo com as preferências do público-alvo.

## Estrutura do Código

O código está organizado em seções correspondentes às etapas da análise, facilitando a compreensão e replicação do processo. As visualizações são apresentadas de forma clara, auxiliando na interpretação dos resultados.

## Conclusão

Este projeto oferece uma visão aprofundada dos fatores que contribuem para o aumento no churn em assinaturas da Petlove. As sugestões fornecidas são baseadas em insights extraídos da análise de dados e destinam-se a orientar a equipe na implementação de estratégias eficazes para redução do churn. A abordagem transparente e documentada visa facilitar a colaboração e garantir a compreensão da análise realizada.

**Autor:** João Paula  

[Link para o Colab](https://colab.research.google.com/drive/1b6l_yV0UmYljFL5Aac52YqCY5pJjJ4kU)
