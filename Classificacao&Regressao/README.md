## 🔍 O que é Aprendizado Supervisionado?

É uma forma de aprendizado de máquina em que o modelo é **treinado com dados rotulados**.  


# 🎯 Classificação

A **classificação** é usada quando a saída é **categórica**.

O modelo analisa os dados e tenta aprender **limites de decisão** que separam as classes.  
Depois, quando recebe uma nova amostra, ele **prediz a qual classe** ela pertence.

### Exemplo Utilizado:
- **Base usada:** *Iris Dataset* (do repositório UCI).  
- **Técnica aplicada:** `K-Nearest Neighbors (KNN)`
- **Etapas realizadas:**
  1. Carregamento e exploração dos dados.  
  2. Divisão em treino e teste.  
  3. Treinamento do modelo.  
  4. Predição de novas amostras.

### 💡 Observação
O KNN decide a classe de um novo ponto observando **os vizinhos mais próximos** no espaço de características.  



# 📈 Regressão

A **regressão** é usada quando a saída é **numérica e contínua**.

O modelo tenta **encontrar uma relação matemática** entre as variáveis de entrada (X) e a saída (y).  
A ideia é achar uma **função** que melhor represente essa relação, minimizando os erros de previsão.

### Exemplo Utilizado:
- **Base usada:** *Boston Housing Dataset*.  
- **Técnica aplicada:** `Regressão Linear`.  
- **Etapas realizadas:**
  1. Leitura e análise das variáveis.  
  2. Separação dos dados em treino e teste.  
  3. Treinamento do modelo linear.  
  4. Cálculo da métrica **R²**, que indica o quão bem o modelo explica os dados.