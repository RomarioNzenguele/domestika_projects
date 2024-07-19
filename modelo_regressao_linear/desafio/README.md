## [DESAFIO] Crie um modelo de regressão linear para prever o peso PRÁTICA 3.1

À semelhança do que foi feito na lição "Seu primeiro modelo: regressão linear", você vai criar um modelo que, com base na altura de uma pessoa (em metros), deve prever o peso (em Kg).

- Crie um novo arquivo CSV semelhante ao arquivo Celsius/Fahrenheit, só que ele conterá dados de altura e peso.
- Insira pelo menos 10 registros de altura e seu peso correspondente. Eles podem ser dados de sua família, amigos ou da Internet.
- Treine o modelo de regressão linear, como na lição "Seu primeiro modelo: regressão linear".
- Uma vez treinado, ele tenta fazer previsões, inserindo uma altura e retorna o peso estimado.
- Funciona bem ou não? Por que você acha que é assim?

**By: Domestika**

***

## [SOLUÇÃO]

Para a atividade utilizei dois conjuntos de dados, retirados do kaggle, tendo trabalhado com dois cases:

- __Case 1:__ [FIFA23 OFFICIAL DATASET(CLEAN DATA)](https://www.kaggle.com/datasets/kevwesophia/fifa23-official-datasetclean-data?select=CLEAN_FIFA23_official_data.csv) - Dados dos Jogadores FIFA23
- __Case 2:__ [BMI Analysis](https://www.kaggle.com/datasets/rukenmissonnier/age-weight-height-bmi-analysis?select=bmi.csv) - Dados de análise de IMC de 741 indivíduos
  
Usando nos dois cases as variáveis peso e altura, foi possível verificar uma diferença na avaliação dos modelos, visto que um trabalha com dados de pessoas consideradas saudáveis (Jogadores) e outra com diferentes indivíduos com distintos estados de saúde. Isso demostra que o Case 1 é o tipo de case apropriado para realização de previsões do género por estar mais próximo da realidade.

**Dica: acredito que se trabalharmos apenas com os pesos normais do case 2, a avaliação do modelo melhoraria considerávelmente!**
