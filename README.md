# Neural Network Optimization with Optuna

## Estrutura do Projeto


Este projeto demonstra um fluxo de trabalho completo para treinar, otimizar e servir um modelo de classificação de rede neural usando PyTorch. A otimização de hiperparâmetros é realizada com a biblioteca Optuna.

## Estrutura do Repositório

- **/dados**:
  - `Expressao_genica_alvos_endocnabinoides_classificacao.xlsx`: O dataset utilizado para o treinamento. (Você deve criar esta pasta e adicionar seu arquivo)
- **/artefatos**:
  - `melhor_modelo.pth`: O checkpoint do modelo treinado, contendo os pesos, a arquitetura e os objetos de pré-processamento (scaler e encoder).
  - `melhores_hyperparametros.json`: Arquivo JSON com os melhores hiperparâmetros encontrados pelo Optuna.
- `treinamento_e_otimizacao.ipynb`: Notebook com o código completo para carregar os dados, otimizar os hiperparâmetros e treinar o modelo final.
- `predicao_com_modelo_treinado.ipynb`: Notebook de exemplo que mostra como carregar o modelo e os artefatos salvos para fazer novas predições.
- `requirements.txt`: Lista de dependências Python para configurar o ambiente.

## Como Usar

### 1. Configuração do Ambiente

Primeiro, clone o repositório e instale as dependências necessárias:

```bash
git clone https://github.com/viniciusbon/deep_learning_classification_endocanabinoides.git
cd <deep_learning_classification_endocanabino>
pip install -r requirements.txt