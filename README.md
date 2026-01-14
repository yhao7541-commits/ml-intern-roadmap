# PyTorch CIFAR10 Training System

A clean and reproducible CIFAR10 image classification training pipeline built with PyTorch.

## Features
- Modular project structure
- Data augmentation
- TensorBoard logging
- Checkpoint & resume training
- Command-line configuration
- Reproducible training with random seed

## Project Structure
data/
models/
checkpoints/
logs/
train.py
test.py
## Requirements
- Python >= 3.8
- PyTorch
- torchvision

## Training
```bash
python train.py --epochs 30 --batch_size 64
## Resume Training
```bash
python train.py --resume
## Evaluation
```bash
python test.py
