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

## Antes de começar

1. Abra o notebook no Colab pelo badge acima.
2. Vá em **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU (T4)**.
3. Rode a primeira célula (diagnóstico) e confira que a GPU aparece.

A GPU é opcional na Aula 1, mas **obrigatória nas Aulas 2 e 3** — a Aula 2 treina uma ResNet34 e a
Aula 3 roda Faster R-CNN e Mask R-CNN; nenhuma das duas termina em tempo razoável na CPU.

Se quiser rodar localmente, veja as
[instruções de instalação do PyTorch](https://pytorch.org/get-started/locally/).


## Créditos

Material adaptado dos notebooks da disciplina, de autoria de Lívia Cereja.
