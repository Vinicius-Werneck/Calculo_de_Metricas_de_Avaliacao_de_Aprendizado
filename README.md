# 📌 Classificação de Dígitos MNIST com Redes Neurais e Cálculo de Métricas de Avaliação de Aprendizado.

Este repositório contém um projeto de aprendizado de máquina que utiliza uma rede neural artificial para classificar dígitos manuscritos do famoso conjunto de dados MNIST. O modelo foi treinado para reconhecer os dígitos de 0 a 9 e avaliado com base em métricas de classificação, como acurácia, sensibilidade, especificidade, precisão e F-score.

---

## 📌 Tecnologias Utilizadas
- Python 3.x
- TensorFlow/Keras
- NumPy
- Pandas
- Scikit-Learn

---

## 📌 Como Executar o Projeto

### 🔹 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/mnist-classificacao.git](https://github.com/Vinicius-Werneck/Calculo_de_Metricas_de_Avaliacao_de_Aprendizado.git
cd mnist-classificacao
```

### 🔹 2. Instale as Dependências
Certifique-se de que o ambiente virtual está ativado e instale os pacotes necessários:
```bash
pip install tensorflow scikit-learn pandas numpy jupyterlab
```

### 🔹 3. Abra o JupyterLab e execute o notebook:
```bash
jupyter lab
```
```bash
calculo_metricas.ipynb
```

---

## 📌 Estrutura do Projeto
```
mnist-classificacao/
│── mnist_classification.py  # Script principal
│── requirements.txt         # Lista de dependências
│── README.md                # Documentação do projeto
└── results/                 # Pasta para armazenar resultados e saídas
```

---

## 📌 Explicação do Modelo
O modelo de rede neural utilizado tem a seguinte arquitetura:
- Camada de entrada: 784 neurônios (28x28 pixels achatados)
- Camada oculta 1: 128 neurônios (ReLU)
- Camada oculta 2: 64 neurônios (ReLU)
- Camada de saída: 10 neurônios (Softmax para classificação multiclasse)

A função de perda utilizada é **categorical_crossentropy** e o otimizador é **Adam**.

---

## 📌 Avaliação do Modelo
Após o treinamento, o modelo foi avaliado utilizando a matriz de confusão e as seguintes métricas:
- **Acurácia**: Percentual total de previsões corretas.
- **Sensibilidade (Recall)**: Capacidade de identificar corretamente cada dígito.
- **Especificidade**: Proporção de dígitos corretamente excluídos de uma classe.
- **Precisão**: Percentual de previsões corretas para cada classe.
- **F-score**: Equilíbrio entre precisão e recall.

Exemplo de saída do modelo:
```
           Sensibilidade  Especificidade  Acurácia  Precisão  F-score
Dígito 0      0.985714       0.998448   0.9972   0.985714  0.985714
Dígito 1      0.987665       0.999998   0.9978   0.992914  0.990283
...
```
---

## 📌 Possíveis Melhorias
🔹 Ajuste de hiperparâmetros (número de neurônios, camadas, taxa de aprendizado)
🔹 Data Augmentation para melhorar generalização
🔹 Uso de redes neurais convolucionais (CNN) para melhor desempenho

---

## 📌 Contribuições
Pull requests são bem-vindos! Sinta-se à vontade para abrir uma *issue* para sugestões e melhorias.

✉️ Entre em contato: viniciusonrj@gmail.com

---

🚀 **Happy Coding!** 🚀

