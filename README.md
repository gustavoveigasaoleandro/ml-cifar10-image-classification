# ml-cifar10-image-classification

Projeto de classificação de imagens usando o dataset CIFAR-10. O foco é demonstrar um fluxo de deep learning para reconhecer categorias visuais a partir de imagens pequenas.

## Conteúdo

- `cifar10_classification.ipynb`: notebook com carregamento dos dados, preparação, treino e avaliação.
- `.gitignore`: exclusões de cache, ambiente virtual e artefatos locais.

## Objetivo do Estudo

O notebook cobre conceitos práticos de visão computacional:

- carregamento de dataset padrão;
- normalização de imagens;
- definição de arquitetura neural;
- treinamento supervisionado;
- avaliação por acurácia e comportamento de validação;
- interpretação básica dos resultados.

## Base de Dados

O CIFAR-10 e um dataset clássico de classificação com 10 classes de objetos. A base é normalmente carregada diretamente por bibliotecas de deep learning, entao os arquivos brutos não precisam ser versionados neste repositório.

## Como Executar

1. Instale as dependências principais, como `tensorflow`, `numpy` e `matplotlib`.
2. Abra o notebook:

```bash
jupyter notebook cifar10_classification.ipynb
```

3. Execute as células em ordem para baixar/carregar o dataset e treinar o modelo.

## Limitações

Este projeto é um estudo didático. Ele não inclui empacotamento para produção, API de inferência ou ajuste fino extensivo de hiperparâmetros.
