# Neural Network Optimization with Optuna

## Estrutura do Projeto


Este projeto foi inicialmente desenvolvido para avaliar a possibilidade de classificação de alvos do sistema endocanabinoide em grupos com faixas etárias distintas, aqui demonstro como carregar o modelo que foi treinado e otimizado para classificação usando PyTorch. A otimização de hiperparâmetros foi realizada com a biblioteca Optuna.

As features compõe: 
-Receptor Canabinoide tipo 1
-Receptor Canabinoide tipo 2
-Enzima de síntese de anandamida (endocanabinoide mais abundante)
-Enzima de degradadação de anandamida
-Enzima de síntese de 2-araquidonilglicerol(segundo endocanabinoide descoberto e mais abundante)
-Enzima de degradadação de 2-araquidonilglicerol

## Estrutura do Repositório

- **/artefatos**:
  - `melhor_modelo.pth`: Os salvos do modelo treinado, contendo os pesos, a arquitetura e os objetos de pré-processamento (scaler e encoder).
- `requirements.txt`: Lista de dependências Python para configurar o ambiente.

## Como Usar

### 1. Configuração do Ambiente

Primeiro, clone o repositório e instale as dependências necessárias:

```bash
git clone https://github.com/viniciusbon/deep_learning_classification_endocanabinoides.git
cd deep_learning_classification_endocanabinoides

pip install -r requirements.txt


