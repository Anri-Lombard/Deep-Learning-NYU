# NYU Deep Learning (Spring 2020), worked through in PyTorch

My notebooks, slides and notes from working through **NYU DS-GA 1008 Deep Learning** taught by
[Yann LeCun](http://yann.lecun.com/) and [Alfredo Canziani](https://atcold.github.io/), organised by course week.

The notebooks come from the course's practica in Alfredo Canziani's
[NYU-DLSP20 repository](https://github.com/Atcold/NYU-DLSP20). Here they are run end to end, with outputs saved,
and with my solutions to the exercises where the notebooks leave them open (for example the logic-neuron exercises in Week 1).

## Course links

- Course website: [atcold.github.io/NYU-DLSP20](https://atcold.github.io/NYU-DLSP20/)
- Original notebooks and slides: [Atcold/NYU-DLSP20](https://github.com/Atcold/NYU-DLSP20)
- Lecture videos: [NYU Deep Learning SP20 playlist](https://www.youtube.com/playlist?list=PLLHTzKZzVU9eaEyErdV26ikyolxOsz6mq)

## Contents

| Week | Topics | Notebooks | Slides |
|---|---|---|---|
| [1](Week%201/) | History and motivation, evolution of DL, neural nets | [00 Logic neuron programming](Week%201/Notebooks/00-logic_neuron_programming.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%201/Notebooks/00-logic_neuron_programming.ipynb)<br>[01 Tensor tutorial](Week%201/Notebooks/01-tensor_tutorial.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%201/Notebooks/01-tensor_tutorial.ipynb)<br>[02 Space stretching](Week%201/Notebooks/02-space_stretching.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%201/Notebooks/02-space_stretching.ipynb) | [Intro](Week%201/001-intro.pdf) |
| [2](Week%202/) | SGD and backpropagation, backprop in practice, NN training | [04 Spiral classification](Week%202/Notebooks/04-spiral_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%202/Notebooks/04-spiral_classification.ipynb)<br>[05 Regression](Week%202/Notebooks/05-regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%202/Notebooks/05-regression.ipynb) | [Backprop](Week%202/002-backprop.pdf), [Spiral classification](Week%202/01%2520-%2520Spiral%2520classification.pdf) |
| [3](Week%203/) | Parameter transformations, ConvNets, properties of natural signals | [06 ConvNet](Week%203/Notebooks/06-convnet.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%203/Notebooks/06-convnet.ipynb) | [ConvNets](Week%203/003-convnet.pdf), [CNN](Week%203/02%20-%20CNN.pdf) |
| [4](Week%204/) | Linear algebra and 1D convolutions | [07 Listening to kernels](Week%204/Notebooks/07-listening_to_kernels.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%204/Notebooks/07-listening_to_kernels.ipynb) | |
| [5](Week%205/) | Optimisation, autograd, convolutions revisited | [03 Autograd tutorial](Week%205/Notebooks/03-autograd_tutorial.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%205/Notebooks/03-autograd_tutorial.ipynb)<br>[Custom gradients](Week%205/Notebooks/b-custom_grads.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%205/Notebooks/b-custom_grads.ipynb) | [Optimisation](Week%205/004-optimization.pdf) |
| [6](Week%206/) | ConvNet applications, RNNs and attention, training RNNs | [08 Sequence classification](Week%206/Notebooks/08-seq_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%206/Notebooks/08-seq_classification.ipynb)<br>[09 Echo data](Week%206/Notebooks/09-echo_data.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%206/Notebooks/09-echo_data.ipynb) | [ConvNets II](Week%206/005-convnet2.pdf), [Architectures](Week%206/006-architectures.pdf), [RNN](Week%206/04%20-%20RNN.pdf) |
| [7](Week%207/) | Energy-based models, self-supervised learning, autoencoders | [10 Autoencoder](Week%207/Notebooks/10-autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%207/Notebooks/10-autoencoder.ipynb) | [EBM I](Week%207/007-ebm-01.pdf), [Generative models](Week%207/05%20-%20Generative%20models.pdf) |
| [8](Week%208/) | Contrastive methods, regularised latent variables, variational autoencoders | [11 VAE](Week%208/Notebooks/11-VAE.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%208/Notebooks/11-VAE.ipynb) | [EBM II](Week%208/008-ebm-02.pdf), [Generative models](Week%208/05%20-%20Generative%20models.pdf) |
| [9](Week%209/) | Sparsity, world models, GANs | [DCGAN script](Week%209/dcgan/) | [EBM III](Week%209/009-ebm-03.pdf), [Generative models](Week%209/05%20-%20Generative%20models.pdf) |
| [10](Week%2010/) | Self-supervised learning in vision, predictive control | [14 Truck backer-upper](Week%2010/Notebooks/14-truck_backer-upper.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%2010/Notebooks/14-truck_backer-upper.ipynb) | [SSL](Week%2010/010-ssv.pdf), [Controller learning](Week%2010/09%20-%20Controller%20learning.pdf) |
| [11](Week%2011/) | Activations, losses, prediction and policy learning under uncertainty (PPUU) | | [EBM IV](Week%2011/011-ebm-04.pdf), [Activations](Week%2011/011-pytorch-activations.pdf), [Losses](Week%2011/011-pytorch-losses.pdf), [PPUU](Week%2011/20190703%20-%20PPUU.pdf) |
| [12](Week%2012/) | Deep learning for NLP, attention and transformers | [15 Transformer](Week%2012/Notebooks/15_transformer.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%2012/Notebooks/15_transformer.ipynb) | [Language](Week%2012/012-language.pdf), [Attention & transformer](Week%2012/10%20-%20Attention%20%26%20transformer.pdf) |
| [13](Week%2013/) | Graph convolutional networks | [16 Gated GCN](Week%2013/Notebooks/16-gated_GCN.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%2013/Notebooks/16-gated_GCN.ipynb) | [GCN](Week%2013/013-gcn.pdf), [GCN practicum](Week%2013/11%20-%20GCN.pdf) |
| [14](Week%2014/) | Structured prediction, graphical methods, regularisation and Bayesian NNs | [12 Regularisation](Week%2014/Notebooks/12_regularization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%2014/Notebooks/12_regularization.ipynb)<br>[13 Bayesian NN](Week%2014/Notebooks/13-bayesian_nn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anri-Lombard/Deep-Learning-NYU/blob/main/Week%2014/Notebooks/13-bayesian_nn.ipynb) | [Structured prediction](Week%2014/014-structpred.pdf), [Regularisation](Week%2014/07%20-%20Regularisation.pdf), [Bayesian NN](Week%2014/08%20-%20Bayesian%20NN.pdf) |
| [15](Week%2015/) | Inference and training for latent-variable EBMs | | [EBM](Week%2015/12%20-%20EBM.pdf) |

Notebook numbers follow the course repo, so they don't always line up with the week they were covered in.

## Running the notebooks

Locally (recommended, since several notebooks import helper files that sit next to them):

```bash
git clone https://github.com/Anri-Lombard/Deep-Learning-NYU.git
cd Deep-Learning-NYU
pip install torch torchvision matplotlib numpy jupyter
jupyter notebook
```

Some notebooks need extra packages: `librosa` (Week 4), `torchviz` (Week 5), `opencv-python` (Week 7), `scikit-learn` (Week 8),
`tqdm` (Week 10), `torchtext` (Weeks 12 and 14), `dgl` and `networkx` (Week 13). The notebooks were written against
2020-era PyTorch, so newer `torchtext` and `dgl` releases may need small API changes.
MNIST is downloaded by `torchvision` on first run.

On Colab, use the badges above. Notebooks that import `plot_lib` or `sequential_tasks`, or show images from `res/`,
need those files uploaded to the Colab session first (they're in the same `Notebooks/` folder, or in [`res/`](res/)).

## Credit and license

All course material (lectures, slides, and the original notebooks) is by Yann LeCun, Alfredo Canziani and the NYU
Center for Data Science, released under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) in [Atcold/NYU-DLSP20](https://github.com/Atcold/NYU-DLSP20).
The Week 9 DCGAN script is from [pytorch/examples](https://github.com/pytorch/examples/tree/main/dcgan).
This repository is shared under the same licence, CC BY-NC-SA 4.0 (see [LICENSE](LICENSE)).

I'm not affiliated with NYU, Yann LeCun or Alfredo Canziani; this is just a student's record of learning from the
material they generously made public. Any mistakes in the solutions are mine, so feel free to open an issue if you spot one.
