# Trabalho Final de IA

Mestrado Profissional em Computação Aplicada

Professor: Dr. Jefferson O. Andrade

## Metas do Projeto

- Detectar fraudes em transações de cartão de crédito com aprendizado não supervisionado utilizando o algoritmo One-class SVM;

- Comparar a performance de detecção de fraude utilizando 4 diferentes núcleos do One-class SVM.

## Abordagem

- Obter a base de transações de cartões de crédito européia disponível publicamente no [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud#creditcard.csv)

- Usar transformação de distribuição normal nos dados para que cada dimensão tenha média 0 e desvio padrão 1

- Separar a base aleatoriamente em 80% para treino e 20% para testes

- Construir o algoritmo principal usando Python 3

- Utilizar scikit-learn para construir o One-class SVM

- Executar o algoritmo seguindo os passos abaixo, uma vez para cada tipo de núcleo do One-class SVM
  - Utilizar a base de treino para teste do algoritmo (80%)
  - Utilizar os 20% da base de teste como entrada do algoritmo e registar cada saída detectada

- Ao final, os resultados serão colocados em uma matriz de confusão para análise de performance

## Bibliografia

SHAKYA, Ronish. Application of machine learning techniques in credit card fraud
detection. 2018.

NIU, Xuetong; WANG, Li; YANG, Xulei. A comparison study of credit card fraud
detection: Supervised versus unsupervised. 2019.
