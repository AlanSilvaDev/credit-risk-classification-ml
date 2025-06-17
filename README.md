📊 Sistema de Classificação de Crédito com Machine Learning

Este projeto tem como objetivo desenvolver e comparar modelos de classificação de crédito para prever a inadimplência de clientes, utilizando algoritmos de Machine Learning supervisionado com base em métricas robustas e validação cruzada.

🎯 Objetivo:

Construir modelos preditivos capazes de identificar com alta precisão quais clientes possuem maior risco de inadimplência, ajudando instituições financeiras a tomarem decisões mais seguras e estratégicas.

🧪 Modelos Utilizados:

Foram implementados, treinados e avaliados três modelos principais:

🌳 Árvore de Decisão

🤖 Máquina de Vetores de Suporte (SVM)

🧠 Rede Neural (MLPClassifier)


📈 Métricas Avaliadas:

Para avaliar a performance dos modelos, foram utilizadas as seguintes métricas:

Acurácia

Precisão

Recall

F1-Score

AUC (Área sob a Curva ROC)

Validação Cruzada Repetida




✅ Resultados


Modelo  	         Acurácia	   Precisão 	  Recall	   F1-Score 	  AUC


Árvore de Decisão	 0.9817	     0.9221	      0.9342     0.9281	      0.9614


SVM              	0.9767	     0.8523     	0.9868	   0.9146     	0.9984


Rede Neural      	0.9950	     0.9867      	0.9737	   0.9801	      0.9998



🔁 Validação Cruzada (10 folds × 8 repetições):

Árvore: 0.9891 ± 0.0092

SVM: 0.9837 ± 0.0058

Rede Neural: 0.9990 ± 0.0019



📌 Conclusões:

A Rede Neural se destacou com a melhor performance geral, apresentando altíssima acurácia, precisão e AUC, além de excelente estabilidade na validação cruzada.

O SVM foi especialmente eficaz no recall, sendo ideal para cenários onde não detectar um inadimplente representa alto risco.

A Árvore de Decisão demonstrou bom equilíbrio e ótima explicabilidade, sendo uma opção eficiente para sistemas que exigem interpretabilidade.



🚀 Tecnologias Utilizadas:


Python (scikit-learn, numpy, matplotlib, seaborn)

Jupyter Notebook

Machine Learning supervisionado

Validação Cruzada com RepeatedStratifiedKFold


