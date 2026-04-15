# ml-cifar10-image-classification

Projeto de classificacao de imagens usando o dataset CIFAR-10. O foco e demonstrar um fluxo de deep learning para reconhecer categorias visuais a partir de imagens pequenas.

## Conteudo

- `cifar10_classification.ipynb`: notebook com carregamento dos dados, preparacao, treino e avaliacao.
- `.gitignore`: exclusoes de cache, ambiente virtual e artefatos locais.

## Objetivo do Estudo

O notebook cobre conceitos praticos de visao computacional:

- carregamento de dataset padrao;
- normalizacao de imagens;
- definicao de arquitetura neural;
- treinamento supervisionado;
- avaliacao por acuracia e comportamento de validacao;
- interpretacao basica dos resultados.

## Base de Dados

O CIFAR-10 e um dataset classico de classificacao com 10 classes de objetos. A base e normalmente carregada diretamente por bibliotecas de deep learning, entao os arquivos brutos nao precisam ser versionados neste repositorio.

## Como Executar

1. Instale as dependencias principais, como `tensorflow`, `numpy` e `matplotlib`.
2. Abra o notebook:

```bash
jupyter notebook cifar10_classification.ipynb
```

3. Execute as celulas em ordem para baixar/carregar o dataset e treinar o modelo.

## Limitacoes

Este projeto e um estudo didatico. Ele nao inclui empacotamento para producao, API de inferencia ou ajuste fino extensivo de hiperparametros.
