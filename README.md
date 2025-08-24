
# 📊 Predição de Evasão Escolar com Machine Learning

Este projeto tem como objetivo prever **evasão escolar** utilizando técnicas de **análise de dados** e **aprendizado de máquina**.  
O projeto foi desenvolvido no formato de **notebook Jupyter/Google Colab** e está organizado em etapas claras de coleta de dados, exploração, modelagem e conclusões.

---

## 📂 Estrutura do Projeto

- `analise_evasao.ipynb` → Notebook principal com todo o fluxo do projeto.
- `modelo_evasao.joblib` → Modelo treinado e salvo para futuras predições.
- `README.md` → Documentação do projeto.

---

## 🛠️ Etapas do Projeto

### 1. Coleta de Dados
Foi gerado um **dataset sintético** representando informações acadêmicas e socioeconômicas dos alunos, incluindo variáveis como:
- Idade
- Sexo
- Frequência escolar
- Nota média
- Se trabalha ou não
- Apoio familiar
- Evasão (variável alvo: 0 = não evadiu, 1 = evadiu)

### 2. Análise Exploratória (EDA)
Foram analisadas distribuições das variáveis e a proporção de alunos que evadiram.  
Exemplo: cerca de **30% dos alunos apresentaram evasão** no dataset gerado.

### 3. Modelagem
Foram testados três algoritmos de machine learning:
- **Regressão Logística**
- **Árvore de Decisão**
- **Random Forest**

A avaliação foi feita usando **classification report (precisão, recall e F1-score)** e **matriz de confusão**.

### 4. Resultados
- O modelo de **Regressão Logística** apresentou o melhor equilíbrio entre precisão e recall.  
- Foi escolhido como **modelo final** e salvo no arquivo `modelo_evasao.joblib`.

### 5. Conclusões
- O uso de machine learning é útil para identificar perfis de alunos com maior risco de evasão.  
- A análise pode apoiar políticas educacionais no direcionamento de ações de prevenção.  
- O projeto pode ser expandido futuramente com dados reais, tuning de hiperparâmetros e novas variáveis.

---

## 🚀 Como Executar

1. Clone este repositório ou baixe os arquivos.  
2. Abra o arquivo `analise_evasao.ipynb` no **Google Colab** ou **Jupyter Notebook**.  
3. Execute as células em ordem.  
4. O modelo treinado será salvo como `modelo_evasao.joblib`.

---

## 📌 Tecnologias Utilizadas
- Python 3
- Pandas, Numpy
- Matplotlib
- Scikit-learn
- Joblib

---

## 👨‍💻 Autor
Projeto desenvolvido por **Euller Tales Santos de Souza** como parte do aprendizado em **Análise de Dados**.

