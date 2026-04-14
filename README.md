# CIFAR-10 Image Classification

Projeto acadêmico de classificação de imagens com o dataset CIFAR-10 usando TensorFlow/Keras.

## Conteúdo

- `cifar10_classification.ipynb`: notebook principal com carregamento dos dados, treinamento e avaliação do modelo.

## Objetivo

Treinar e avaliar uma rede neural convolucional para reconhecer as classes do CIFAR-10.

## Requisitos

- Python 3.10+
- Jupyter Notebook ou JupyterLab
- `tensorflow`
- `matplotlib`
- `numpy`
- `scikit-learn`

## Como executar

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter tensorflow matplotlib numpy scikit-learn
jupyter notebook cifar10_classification.ipynb
```

## Observações

- O dataset CIFAR-10 é baixado automaticamente pelo TensorFlow na primeira execução.
- O notebook inclui etapas típicas de visualização, treino, validação e análise de desempenho.
