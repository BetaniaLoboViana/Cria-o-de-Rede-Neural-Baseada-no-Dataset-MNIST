
# Rede Neural para Classificação de Imagens (MNIST)

Este projeto implementa o treinamento de uma rede neural simples para classificar imagens do dataset MNIST (dígitos de 0 a 9) utilizando PyTorch.

## Pré-requisitos

Instale as dependências:

pip install torch torchvision matplotlib numpy

## Como Rodar

1. Clone este repositório:

git clone https://github.com/BetaniaLoboViana/Cria-o-de-Rede-Neural-Baseada-no-Dataset-MNIST.git cd Cria-o-de-Rede-Neural-Baseada-no-Dataset-MNIST

2. Execute o código:

python rede_neural_do_zero.py

## Estrutura do Código

- **Modelo**: Rede neural com 3 camadas totalmente conectadas (fully connected).
- **Treinamento**: Função `treino()` utiliza SGD e NLLLoss para treinar o modelo.
- **Visualização**: Exibe imagens do MNIST durante o treinamento.

## Resultados

Durante o treinamento, a perda média por época será exibida. O modelo treina por 10 épocas, mas pode ser modificado à sua escolha.

