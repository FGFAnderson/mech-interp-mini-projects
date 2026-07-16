# torch-cnn

A simple CNN trained on MNIST in PyTorch, comparing SGD vs Adam optimisers.

## Setup

```bash
uv sync
```

## Usage

Open [TorchCNN.ipynb](TorchCNN.ipynb) and run the cells top to bottom. It will:

1. Download MNIST and split it into train/test sets.
2. Train a small CNN (2 conv layers + a linear head) on GPU if available.
3. Compare training curves for SGD and Adam.
