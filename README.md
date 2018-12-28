# bayes_spam

O presente repositório implementa um classificador textual para spams de SMS utilizando a técnica de Naive-Bayes.

## Dataset:
A implementação abaixo de bayes utiliza o dataset de mensagens de spam de sms fornecito no curso 'Udacity's Machine Learning Engineer Nanodegree'.
 Este dataset é composto de 5572 mensagens de sms classificadas como spam ('spam') ou não spam ('ham').
 
 ## Problema:
O problema solucionado é referente a classificação textual. Neste caso em específico a classificação e detecção de spam em mensagens SMS.

##Pré-processamento:
Não foi realizado nenhum método de pré-processamento mais avançado como stemming ou lemmatização.
Os labels foram trocados, onde spam tornou-se 1 e ham tornou-se 0, como forma de possibilitar a classificação.
Além disso, as mensagens foram convertidas para bag of words antes de serem usadas pelo modelo Bayes.

## Avaliação
Para avaliação optou-se por cross-validaiton com holdout, onde o dataset foi previamente dividido em treino (75%) e teste (25%).

## Resultados
Os resultados obtidos foram bastante satisfatórios, comprovando a aptidão do método de bayes para classificação textual.
Foram obtidos os seguintes resultados:

**Accuracy**: 0.9885139985642498

**Precision**: 0.9720670391061452

**Recall**: 0.9405405405405406

**F1**: 0.9560439560439562
