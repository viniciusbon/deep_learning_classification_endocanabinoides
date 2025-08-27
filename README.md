# Neural Network Optimization with Optuna

## Estrutura do Projeto


Este projeto foi inicialmente desenvolvido para avaliar a possibilidade de classificação de alvos do sistema endocanabinoide, aqui demonstro como carregar o modelo que foi treinado e otimizado para classificação usando PyTorch. A otimização de hiperparâmetros foi realizada com a biblioteca Optuna.

## Estrutura do Repositório

- **/dados**:
  - `Expressao_genica_alvos_endocnabinoides_classificacao.xlsx`: O dataset utilizado para o treinamento. (Você deve criar esta pasta e adicionar seu arquivo)
- **/artefatos**:
  - `melhor_modelo.pth`: Os salvos do modelo treinado, contendo os pesos, a arquitetura e os objetos de pré-processamento (scaler e encoder).
- `requirements.txt`: Lista de dependências Python para configurar o ambiente.

## Como Usar

### 1. Configuração do Ambiente

Primeiro, clone o repositório e instale as dependências necessárias:

```bash
git clone https://github.com/viniciusbon/deep_learning_classification_endocanabinoides.git
cd <deep_learning_classification_endocanabino>

pip install -r requirements.txt

