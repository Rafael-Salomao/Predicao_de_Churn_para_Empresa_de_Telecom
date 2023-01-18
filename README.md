# Predicao_de_Churn_para_Empresa_de_Telecomunicacoes

## 1.0 Introdução

O churn de clientes refere-se ao ciclo natural de negócios de perder e adquirir clientes. Toda empresa – não importa a qualidade de seus produtos ou atendimento ao cliente – experimenta churn. De um modo geral, quanto menos churn você tiver, mais clientes você manterá.

Compreender a rotatividade de clientes é essencial para avaliar a eficácia de seus esforços de marketing e a satisfação geral de seus clientes. Também é mais fácil e barato manter os clientes que você já tem do que adquirir novos. Devido à popularidade dos modelos de negócios de assinatura, é fundamental que muitas empresas entendam onde, como e por que seus clientes podem estar mudando.

## 2.0 Qual problema foi resolvido

O setor de empresas de telecomunicações está entre os mais voláteis, do mercado, e possui um alto nível de concorrência. Diante disso, uma empresa do setor deseja analisar e ter um melhor controle sobre o comportamento de seus clientes e prever potenciais churns. Para, a partir disso, ter insumo para tomar ações, proativamente, a fim de reter esses clientes.

## 3.0 Como foi resolvido

O problema foi resolvido a partir de um modelo estatístico de classificação, em que é atribuído um score para cada cliente, de acordo com seu perfil, considerando as informações contidas na base de dados da empresa. A partir desse score é possível identificar a probabilidade do cliente se tornar um churn, e assim, classificá-lo. Com essa informação, é feita uma análise sobre o perfil de usuários que tendem a ser churn e tomar ações de marketing, melhoria de produto e maior geração de valor, a fim de mantê-los na carteira de clientes da companhia.

## 4.0 Tecnologias utilizadas

- Pandas
- Numpy
- Matplotlib
- Pyplot
- Seaborn
- IPython
- Sklearn
- Imblearn
- Xgboost
- Scikitplot

## 5.0 Resultados obtidos

Para a identificação de classificação dos clientes, foi utilizado o modelo de machine learning: XGBClassifier. O modelo criado aprensenta um recall de 89% para os clientes que são considerados churn. Ou seja, 89% dos clientes do conjunto de teste, que são churn, foram identificados corretamente como churn, pelo modelo construído.

A partir da análise do clientes com perfil para se tornarem churn, foi possível observar alguns comportamentos a serem levados em consideração pelos diretores da empresa de telecomunicações:

- Os cliente que aderem o plano mensal, em sua maioria, tendem a virar churn nos primeiros meses. O que sugere a presença de "curioso", que adquirem a assinatura apenas para testar a funcionalidade do serviço prestado.

- Existe uma tendência de que a maior quantidade de clientes que realizam churn, tem uma mensalidade mais cara

- Para contratos anuais, observa-se um comportamento não padronizado, em que, observa-se picos maiores nos meses em que se encerram ciclos de um ano, como 12, 24, 36, 48 meses. O que sugere uma maior desistência em momentos de renovação de contrato.

Portanto, a partir desses insights e os clientes que serão churn mapeados, é possível elaborar um plano estratégico para retenção desses clientes, gerando mais receita e reduzindo o custo de aquisição de novos clientes - uma vez que reter um cliente tende a ser mais barato do que captar um novo cliente.

## 6.0 Implementações futuras/ evoluções

O projeto é plenamente replicácel em outras empresas reais com contam com modelo de assinaturas. Com o intuito de redução do churn, os insights obtidos podem ser grande valia para tomada de decisões como um novo roadmap do produto, desenvolver novas ferramentas, investir em customer experience, rever preços e agregar mais valor. 

Para isso, seria necessário fazer o deploy do modelo, de modo a unir a inteligência do modelo estatístico criado com a base de clientes e gerar reports para alimentar um dashboard para monitoramento constante dos novos clientes e de suas retenções. Toda via, seria possível entender se as ações tomadas estão surtindo efeito na redução do churn.

Contudo, vale ressaltar a possibilidade de melhoria ao modelo apresentado. Para isso, pode-se implementar outros recursos e ferramentas de análise como: feature selection, identificar variaveis que mais influenciam a variável alvo e trabalhar com feature engineering são artifícios que podem ajudar a melhorar o desempenho do modelo.
