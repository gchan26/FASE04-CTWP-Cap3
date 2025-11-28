# [FIAP] - Implementando Algoritmos de Machine Learning com Scikit-learn
<p align="center">
  <a href="https://www.fiap.com.br/">
    <img src="./images/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" width="40%">
  </a>
</p>

## Membros
- <a>Davis Roberto - RM567941</a>
- <a>Guilherme Chan - RM567722</a>
- <a>Deivid Paula da Silva Oliveira - RM566752</a>
- <a>Guilherme Paes Barreto Didier Garcia - RM568457</a>

# Classificação de Grãos de Trigo com Machine Learning (CRISP-DM)

Este projeto aplica a metodologia CRISP-DM para o desenvolvimento de um modelo de classificação automática de grãos de trigo, utilizando algoritmos de Aprendizado de Máquina.

O objetivo é demonstrar como a automação pode aumentar a eficiência e a precisão na classificação de grãos realizada tradicionalmente de forma manual.

## Dataset

Dataset utilizado: Seeds Dataset  
Fonte: UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/236/seeds

O conjunto contém 210 amostras, distribuídas em três classes:

Classe 1 – Kama  
Classe 2 – Rosa  
Classe 3 – Canadian  

Atributos:
Area  
Perimeter  
Compactness  
Kernel_Length  
Kernel_Width  
Asymmetry_Coeff  
Kernel_Groove_Length  

## Metodologia CRISP-DM

1. Entendimento dos Dados  
Análise estatística, histogramas, boxplots, pairplot, verificação de valores ausentes e padronização dos dados.

2. Modelagem  
Foram utilizados os algoritmos KNN, SVM e Random Forest, com divisão 70% treino e 30% teste.

3. Avaliação  
Acurácia, precisão, recall, F1-score e matriz de confusão.

4. Otimização  
GridSearchCV aplicado ao KNN.

5. Interpretação  
Análise comparativa entre os modelos e relevância das features.

## Resultados

KNN – 90.47%  
SVM – 92.06%  
Random Forest – 90.47%  

O melhor modelo foi o SVM.

## Importância das Features

Kernel_Groove_Length  
Area  
Perimeter  
Kernel_Width  
Kernel_Length  
Compactness  
Asymmetry_Coeff  

## Conclusão

O modelo SVM apresentou o melhor desempenho. As características físicas do grão se mostraram altamente relevantes para a classificação, comprovando a eficiência do uso de Machine Learning no contexto agrícola.

## Como Executar

pip install -r requirements.txt

Abrir o notebook Projeto_Seeds_CRISP_DM.ipynb na pasta notebooks.

## Tecnologias

Python  
Pandas  
NumPy  
Scikit-Learn  
Matplotlib  
Seaborn  

## Licença

Projeto acadêmico desenvolvido para fins educacionais.