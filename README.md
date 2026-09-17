# Deep Learning — Aulas Práticas

Material das aulas práticas da disciplina de Aprendizado Profundo (graduação).
Os notebooks são feitos para rodar no **Google Colab** — não é preciso instalar nada.

> **Como funciona:** em `aulas_praticas/` ficam os notebooks com os exercícios em aberto, que é por
> onde você deve começar. Em `solucoes/` fica a versão resolvida da mesma aula.

| Tópico 💥 | Descrição 📘 | Solução | Feedback |
|:--- |:---|:---|:---|
| [Introdução ao PyTorch e Conceitos Básicos](aulas_praticas/Basics.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/Basics.ipynb) | Tensores, Datasets & DataLoaders, `nn.Module`, loop de treinamento, autograd e um desafio de CNN no Fashion-MNIST. | [notebook](solucoes/Basics.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/solucoes/Basics.ipynb) | [Formulário de feedback](https://forms.gle/29kofDwaRb3uMJR97) |
| [Treinamento: Otimização e Transfer Learning](aulas_praticas/Training.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/Training.ipynb) | Gradient descent na mão, comparação de otimizadores (SGD, Momentum, Nesterov, Adagrad, RMSProp, Adam) e transfer learning com ResNet34 pré-treinada. | [notebook](solucoes/Training.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/solucoes/Training.ipynb) |[Formulário de feedback](https://forms.gle/nPxRExiwJRc5nWvn8) |
| [Object Detection: IoU, NMS e Detectores](aulas_praticas/Object_Detection.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/Object_Detection.ipynb) | IoU e Non-Maximum Suppression implementados do zero, YOLOv5 via `torch.hub`, Faster R-CNN e Mask R-CNN do `torchvision`, e as métricas Precision/Recall/AP. | — (aula guiada, sem exercícios em aberto) | _a definir_ |
| [RNN, LSTM e GRU](aulas_praticas/RNN.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/RNN.ipynb) | Previsão de séries temporais com redes recorrentes: comparação entre RNN simples, LSTM e GRU numa senoide e em séries reais de preço de ação e de clima. | [notebook](solucoes/RNN.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/solucoes/RNN.ipynb) | _a definir_ |
| [GANs: DCGAN e GAN condicional](aulas_praticas/GAN.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/aulas_praticas/GAN.ipynb) | Você implementa o passo de treino de uma DCGAN que gera rostos, investiga o espaço latente (o que muda quando o ruído $z$ vem de outra distribuição) e constrói uma GAN condicional no Fashion-MNIST. | [notebook](solucoes/GAN.ipynb) [![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erickslb/deep-learning-fgv-2026/blob/main/solucoes/GAN.ipynb) | _a definir_ |

## Antes de começar

1. Abra o notebook no Colab pelo badge acima.
2. Vá em **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU (T4)**.
3. Rode a primeira célula (diagnóstico) e confira que a GPU aparece.

A GPU é **obrigatória nas Aulas 2, 3 e 5** — a Aula 2 treina uma ResNet34, a Aula 3 roda Faster
R-CNN e Mask R-CNN, e a Aula 5 treina duas GANs; nenhuma delas termina em tempo razoável na CPU.
Nas Aulas 1 e 4 ela é opcional: as redes são pequenas e rodam na CPU sem incômodo.

Se quiser rodar localmente, veja as
[instruções de instalação do PyTorch](https://pytorch.org/get-started/locally/).

## Notion com material do curso

[Deep Learning --- 2026.2](https://app.notion.com/p/Deep-Learning-2026-2-3bc7a88448a680eeb110ea3cd3931d48)

## Créditos

Material adaptado dos notebooks da disciplina, de autoria de Lívia Cereja.
