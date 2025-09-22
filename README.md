# Perceptron Supervised Learning

This repository contains the practical project **"Supervised Learning with the Perceptron Neuron"**, developed for the **Artificial Neural Networks** course (2025.2) at **Universidade do Estado do Amazonas (UEA)**.  

The objective is to implement Rosenblatt's Perceptron training algorithm in Python, applying it to classification problems using supervised learning. The project is divided into three main parts:

---

## 📚 Project Structure

### Part I – Linearly Separable Problem
- Training the Perceptron with dataset `dataAll.txt`.
- Using step activation function (ϑ = 0).
- Learning rate: η = 0.1.
- Weights initialized randomly from U(−0.5, +0.5).
- Algorithm runs until convergence (no classification errors).
- Outputs:
  - Number of weight adjustments.
  - Number of epochs until convergence.
  - Scatter plot with decision boundary.

### Part II – Experimentation
- Training repeated 10 times for 6 different configurations:
  - η ∈ {0.4, 0.1, 0.01}.
  - Initial weights ∈ {U(−100, +100), U(−0.5, +0.5)}.
- For each configuration:
  - Mean and standard deviation of weight adjustments.
  - Minimum epochs to converge.
- Results presented in a comparative table (using `prettytable`).

### Part III – Holdout Validation (Non-Linearly Separable Problem)
- Dataset: `dataHoldout.txt`.
- Data split: 70% training / 30% testing.
- Training Perceptron with 100 epochs (weights initialized in U(−0.5, +0.5)).
- Evaluation metrics (using `sklearn.metrics`):
  - Confusion matrix
  - Accuracy
  - Precision, Recall, and F-Score
- Scatter plots:
  - Training data with decision boundary
  - Test data with decision boundary

---

## 🛠️ Technologies Used

- **Python 3.6+**
- **NumPy** – Matrix operations (mandatory).
- **Matplotlib** – Data visualization.
- **Random** and **Math** – Auxiliary operations.
- **Scikit-learn** – Performance metrics only.
- **PrettyTable** – Tabular results (experimentation part).

---

## 👥 Team Members

- **Juliana Ballin Lima**  
  Registration: 2315310011  
  [GitHub Profile](https://github.com/JulianaBallin)  

- **Marcelo Heitor de Almeida Lira**  
  Registration: 2315310043  
  [GitHub Profile](https://github.com/Marcelo-Heitor-de-Almeida-Lira)  

- **Lucas Maciel Gomes**  
  Registration: 2315310014  
  [GitHub Profile](https://github.com/lucassmaciel)  

- **Ryan da Silva Marinho**  
  Registration: 2315310047  
  [GitHub Profile](https://github.com/RyanDaSilvaMarinho)  

- **Vitória Gabrielle Kinshasa Silva de Almeida**  
  Registration: 2415280044  
  [GitHub Profile](httos://github.com/VitoriaKinshasa)

---

## 🔗 Useful Links

- [NumPy Documentation](https://numpy.org/doc/stable/)  
- [Matplotlib Scatter Plots](https://matplotlib.org/3.3.0/api/_as_gen/matplotlib.pyplot.scatter.html)  
- [Python Data Science Handbook – Scatter Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.02-simple-scatter-plots.html)  
- [Google Colab](http://colab.research.google.com/)  

## Instalação e Configuração

Este projeto utiliza o "uv" para gerenciamento de dependências. É necessário instalá-lo no seu computador:

### Instalação do UV

**Windows:**
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
``` 

**MacOS | Linux:**
```
curl -LsSf https://astral.sh/uv/install.sh | sh
``` 

### Configuração do Ambiente

Após instalar o UV, execute o comando abaixo na raiz do projeto:
```
uv sync
``` 

Este comando irá:
- Criar o ambiente virtual (.venv)
- Instalar todas as dependências necessárias

Caso a versão do python não seja instalada com 'uv sync', utilize:
```
uv python install
``` 
Este comando irá:
- Instalar a versão correta do Python para o projeto
---
