# Segmentação de Clientes com K-Means

## Descrição do Projeto
Este projeto aplica técnicas de machine learning não supervisionado para segmentar clientes com base em idade, renda anual e score de gastos. 

Dataset utilizado disponibilizado na plataforma [Kaggle](https://www.kaggle.com/).

 Foi utilizado o algoritmo K-Means na tentativa identificar padrões de comportamento e agrupar clientes em perfis distintos.

## Objetivo da Segmentação
O objetivo é entender os diferentes perfis de clientes para maximizar lucros com estratégias de marketing, fidelização e personalização de ofertas.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Kaggle (fonte do dataset)

## Principais Insights
- Identificação de um grupo premium com alta renda e alto score de gastos
- Detecção de clientes médios com comportamento misto
- Clusterização revelou sobreposição entre alguns grupos, sugerindo limitações do K-Means
    - Teste com outros valores para 'k' se mostrou ineficiente.
- Silhouette Score indicou segmentação moderada, com espaço para melhorias

 Dos cinco clusters gerados pelo modelo, a análise visual indica que os grupos 0 e 3 compartilham do mesmo perfil de cliente médio, com renda e escore por volta de 50. Dos 3 cluters restantes, o cluster 1 necessita de atenção, se destacando como um perfil de cliente premium, com alta renda média e engajamento.
 
Essa interpretação do algoritmo permite ações direcionadas e sugere que a segmentação precisa ser complementada por análise humana.
