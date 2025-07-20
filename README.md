# 🧠 Implementação de MLP e CNN 

Este repositório contém uma atividade prática da disciplina Introdução à Aprendizagem Profunda, com foco na comparação entre redes neurais do tipo **MLP (Multilayer Perceptron)** e **CNN (Convolutional Neural Network)**.

## 🎯 Objetivo

O principal objetivo desta atividade é compreender e implementar duas arquiteturas de redes neurais para resolver tarefa de regressão para a MLP e classificação de imagens para a CNN. Os modelos são avaliados com base em métricas de desempenho e visualizações dos resultados.

## 🗂 Conteúdo do Projeto

- `MLP_CNN.ipynb`: notebook principal contendo:
  - Pré-processamento dos datasets
  - Definição dos modelos MLP e CNN
  - Treinamento e validação
  - Avaliação com métricas como Acurácia e Matriz de Confusão.
  - Visualização dos resultados

## 🧪 Tecnologias e Bibliotecas Utilizadas

- Python
- PyTorch
- torchvision
- NumPy / Matplotlib / scikit-learn

## ⚙️ Estrutura dos Modelos

### 🔹 MLP (Multilayer Perceptron)
- Flatten dos dados de entrada
- Camadas totalmente conectadas com ativação ReLU (ou LeakyReLU)
- Dropout para regularização

### 🔸 CNN (Convolutional Neural Network)
- Camadas convolucionais + pooling
- Camadas densas finais para classificação
- Utilização de técnicas como BatchNorm e Dropout


## 🚀 Como Executar

1. Clone este repositório.
2. Abra o notebook `MLP_CNN.ipynb` no [Google Colab](https://colab.research.google.com/) ou ambiente Jupyter.
3. Execute célula por célula.
4. Experimente modificar hiperparâmetros como taxa de aprendizado, função de ativação ou dropout.

## ✅ Requisitos

- PyTorch e torchvision instalados
- Ambiente Python 3.7+
- Biblioteca scikit-learn

## 📚 Créditos

Esta atividade foi desenvolvida como parte de uma lista prática da disciplina "IF867 - Introdução à Aprendizagem Profunda" do Centro de Informática da Universidade Federal de Pernambuco, com foco no entendimento prático de arquiteturas de redes neurais.

---

> *Este projeto é acadêmico e visa fins educacionais.*
