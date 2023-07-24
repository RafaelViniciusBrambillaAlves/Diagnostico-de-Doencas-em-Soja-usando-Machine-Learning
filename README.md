# 🌱 Soybean

Projeto fictício. O conteúdo apresentado neste projeto, incluindo os dados, não são reais.
***
## 🍃 Contexto e Descrição do Desafio
Bem-vindo ao projeto de Diagnóstico de Doenças em Soja! Neste repositório, exploramos a aplicação de técnicas de Machine Learning para auxiliar no diagnóstico de doenças em plantas de soja. 

O objetivo principal do projeto é desenvolver um modelo de aprendizado de máquina altamente eficiente e preciso para o diagnóstico de doenças em plantas de soja.

***
## 🚜 Etapas do projeto
Pré-processamento dos Dados: Realizamos o pré-processamento dos dados para redimensioná-las, normalizá-las e prepará-las para serem utilizadas como entrada do modelo de Machine Learning.

Modelagem: Utilizamos algoritmos para construir um modelo de classificação capaz de identificar as diferentes doenças em folhas de soja.

Treinamento e Validação: Dividimos o conjunto de dados em conjuntos de treinamento e teste para treinar o modelo e avaliar sua precisão e desempenho.

Avaliação do Modelo: Avaliamos o desempenho do modelo utilizando diversas métricas de avaliação, como acurácia, matriz de confusão, F1-Score, Precisão, Recall e curva ROC.
***
## 🔎 Técnicas de Machine Learning

Naive Bayes: É um algoritmo de classificação probabilística baseado no Teorema de Bayes. É simples, rápido e eficiente, especialmente para classificação de textos e problemas com alta dimensionalidade.

Árvore de Decisão: É um modelo de aprendizado supervisionado que utiliza uma estrutura em forma de árvore para tomar decisões sequenciais com base nas características dos dados.

Seleção de Atributos: É um processo de escolha das características mais relevantes e informativas do conjunto de dados para melhorar o desempenho do modelo e reduzir a dimensionalidade.

Instâncias: Refere-se às observações individuais ou amostras de dados que compõem o conjunto de treinamento ou teste para o modelo de Machine Learning.

Random Forest: É um algoritmo que combina várias árvores de decisão para fazer previsões mais precisas e reduzir o overfitting.

GBM (Gradient Boosting Machine): É uma técnica de Machine Learning que combina várias árvores de decisão fracas para criar um modelo mais forte e melhorar a precisão das previsões.

Rede Neural: É um modelo inspirado na estrutura do cérebro humano, composto por camadas de neurônios interconectados, usado para resolver tarefas complexas de aprendizado de máquina.

Deep Learning: É uma subárea do Machine Learning que utiliza redes neurais profundas para extrair e aprender características complexas de dados não estruturados, como imagens, áudio e texto.
***
## 🥇 Comparação das Técnicas de Machine Learning

A criação do ranking das técnicas de Machine Learning permitirá uma compreensão clara das abordagens mais eficazes para o diagnóstico de doenças em plantas de soja

Precisão (Precision): Proporção de verdadeiros positivos em relação a todas as previsões positivas do modelo

Acurácia (Accuracy): Proporção de previsões corretas em relação ao total de previsões feitas pelo modelo. Mede a exatidão geral das previsões

Recall (Sensibilidade ou Taxa de Verdadeiros Positivos): Proporção de verdadeiros positivos em relação a todas as instâncias reais positivas

F1-Score: Média harmônica entre precisão e recall

<div align="center">

|Técnica | Acurácia | Precisão | Recall | F1-Score |
|--------|----------|----------|--------|----------|
| Naive Baye | 0.8585 | 0.9326 | 0.9384 | 0.9202 |
| Árvore de Decisão | 0.8926 | 0.9154 | 0.9127 | 0.9063 | 
| Seleção de Atributos | 0.8536 | 0.9185 | 0.8733 | 0.8766 |
| Instâncias | 0.8341 | 0.8502 | 0.8565 | 0.8499 |
| Random Forest | 0.9512 | 0.9699 | 0.9690 | 0.9680 |
| GBM | 0.9707 | 0.9840 | 0.9741 | 0.9775 |
| Rede Neural | 0.9219 | 0.9543 | 0.9508 | 0.9514 |
| Deep Learning | 0.9268 | 0.9550 | 0.9388 | 0.9440 |

</div>

***
## 📋 Resultados 

O Gradient Boosting Machine (GBM) obteve o melhor desempenho geral em todas as métricas avaliadas, com uma acurácia de 97.07%, uma precisão de 98.40%, um recall de 97.41% e um F1-Score de 97.75%. Isso indica que o GBM é a técnica mais eficaz para o diagnóstico de doenças em soja entre as listadas.

A Random Forest também apresentou um excelente desempenho, com a segunda melhor acurácia (95.12%) e pontuações muito altas em precisão, recall e F1-Score. Essa técnica mostrou-se bastante efetiva no diagnóstico de doenças em soja.

As técnicas de Naive Bayes, Árvore de Decisão, Rede Neural e Deep Learning também demonstraram bom desempenho, com acurácias superiores a 90% e pontuações consistentes em precisão, recall e F1-Score.

A técnica de Seleção de Atributos apresentou um desempenho satisfatório em termos de acurácia, mas suas métricas de precisão, recall e F1-Score ficaram um pouco abaixo em comparação com outras técnicas.

A técnica de Instâncias teve a menor acurácia e, embora tenha apresentado resultados razoáveis em outras métricas, ficou atrás das outras abordagens.

