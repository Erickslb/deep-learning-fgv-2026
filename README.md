# Deep Learning — Aulas Práticas

Material das aulas práticas da disciplina de Aprendizado Profundo (graduação).
Os notebooks são feitos para rodar no **Google Colab** — não é preciso instalar nada.

> **Como funciona:** em `aulas_praticas/` ficam os notebooks com os exercícios em aberto, que é por
> onde você deve começar. Em `solucoes/` fica a versão resolvida da mesma aula.

| Tópico 💥 | Descrição 📘 | Solução |
|:--- |:---|:---|
| [Introdução ao PyTorch e Conceitos Básicos](aulas_praticas/Basics.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/Basics.ipynb) | Tensores, Datasets & DataLoaders, `nn.Module`, loop de treinamento, autograd e um desafio de CNN no Fashion-MNIST. | [notebook](solucoes/Basics.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/solucoes/Basics.ipynb) |

## Antes de começar

1. Abra o notebook no Colab pelo badge acima.
2. Vá em **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU (T4)**.
3. Rode a primeira célula (diagnóstico) e confira que a GPU aparece.

Se quiser rodar localmente, veja as
[instruções de instalação do PyTorch](https://pytorch.org/get-started/locally/).

## Como estudar com este material

Os notebooks são feitos para serem **executados**, não lidos. Rode cada célula, mude os valores,
quebre de propósito e veja o que acontece — é assim que os shapes e os erros de PyTorch entram na
cabeça. Nos exercícios, tente até travar de verdade antes de olhar a solução.

A solução está disponível desde já, mas ela vale bem menos lida do que reconstruída: o erro que você
cometeu sozinho é o que você não repete na prova. Use-a para conferir o seu resultado e para
comparar abordagens, não como ponto de partida.

## Créditos

Material adaptado dos notebooks da disciplina, de autoria de Lívia Cereja.
