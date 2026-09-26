# 🗳️ Hackathon de Ciência de Dados: O Desafio de 1936
> **Autópsia Estatística, Pós-Estratificação e Modelagem Preditiva da Eleição da Literary Digest**  
> *Projeto apresentado no Summit UMC 2026 | Universidade Mogi das Cruzes (UMC)*

---

## 📌 Sobre o Projeto
Este repositório contém a solução completa desenvolvida para o **Hackathon de Ciência de Dados de 1936**. O objetivo do trabalho é realizar uma investigação estatístico-forense sobre o colapso da famosa pesquisa eleitoral da revista *Literary Digest* na eleição presidencial americana de 1936 (Landon vs. Roosevelt).

Apesar de ter entrevistado mais de 2,4 milhões de eleitores, a revista previu erroneamente a vitória de Alfred Landon com 57% dos votos, enquanto Franklin D. Roosevelt venceu com 62% das urnas e 523 delegados.

Através do uso de **Python**, **Pandas** e **Scikit-Learn**, reponderamos a amostra enviesada usando a eleição de 1932 como âncora (*ground truth*), aplicamos **Regressão Linear** e **SVM**, e recalibramos as estimativas para projetar a vitória real no Colégio Eleitoral.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python 3.10+
- **Ambiente:** Google Colab / Jupyter Notebook
- **Manipulação de Dados:** `pandas`, `numpy`
- **Visualização:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (`LinearRegression`, `SVC`, `StandardScaler`, `train_test_split`)


