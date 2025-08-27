# Classificação de Alvos do Sistema Endocanabinoide com PyTorch e Optuna

Este projeto demonstra um fluxo de trabalho completo para **treinar, otimizar e utilizar um modelo de rede neural para classificação** usando PyTorch. A otimização de hiperparâmetros foi realizada com a biblioteca Optuna.

## 🎯 Sobre o Projeto

O objetivo científico deste modelo é avaliar a possibilidade de classificar grupos de diferentes faixas etárias com base na expressão gênica de alvos do sistema endocanabinoide.

Este repositório fornece não apenas o código para o processo completo de treinamento e otimização, mas também um exemplo claro de como carregar o modelo final pré-treinado para fazer novas predições.

### Features do Modelo

O modelo utiliza as 6 features a seguir, baseadas em dados de expressão gênica relativa:

-   `cnr1`: Receptor Canabinoide tipo 1 (CB1)
-   `cnr2`: Receptor Canabinoide tipo 2 (CB2)
-   `dagl`: Enzima de síntese de 2-araquidonilglicerol (2-AG)
-   `magl`: Enzima de degradação de 2-araquidonilglicerol (2-AG)
-   `nape`: Enzima de síntese de anandamida (AEA)
-   `faah`: Enzima de degradação de anandamida (AEA)

## 🛠️ Bibliotecas Utilizadas

-   **PyTorch**: Framework principal para a construção e treinamento da rede neural.
-   **Optuna**: Biblioteca para otimização de hiperparâmetros.
-   **Scikit-learn**: Utilizada para pré-processamento de dados e avaliação de métricas.
-   **Pandas & NumPy**: Para manipulação e processamento de dados.
-   **Matplotlib & Seaborn**: Para visualização de resultados.

## 📁 Estrutura do Repositório

├── 📄 .gitignore

├── 📜 melhor_modelo.pth       # Save do modelo treinado (pesos, scaler, encoder)

├── 📜 main.ipynb      # Notebook para carregar o modelo e fazer predições

├── 📜 main.py          # Código em Python

└── 📜 requirements.txt     # Dependências do projeto


## 🚀 Como Usar
### 1. Configuração do Ambiente

Primeiro, clone o repositório e instale as dependências necessárias a partir do `requirements.txt`.

```bash
git clone [https://github.com/viniciusbon/deep_learning_classification_endocanabinoides.git](https://github.com/viniciusbon/deep_learning_classification_endocanabinoides.git)
cd deep_learning_classification_endocanabinoides
pip install -r requirements.txt

### 2. Faça o load do modelo com os pesos

### 3. Faça novos predicts 

