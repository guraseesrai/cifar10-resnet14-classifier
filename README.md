# CIFAR-10 Image Classification with Custom ResNet-14

[![PyTorch](https://img.shields.io/badge/pytorch-%E2%89%A52.0-blue)](https://pytorch.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Goal:** Build and train a minimal 14-layer residual network that achieves **≥85 %** test accuracy on CIFAR-10 using modest hardware.

---

## 🚀 Highlights

- **Pure PyTorch** — no external model libraries  
- **Lightweight:** ~5 M parameters (~11 MB on disk)  
- **Configurable CLI** (epochs, batch size, optimizer, LR schedule, warm-up)  
- **Standard augmentations:** random crop + horizontal flip  
- **TensorBoard** integration for live curves & sample images  

---

## 🛠️ Getting Started

### Prerequisites

- Python 3.8+  
- (Optional) GPU for faster training  

### Installation

```bash
git clone https://github.com/your-user/cifar10-resnet14.git
cd cifar10-resnet14
pip install -r requirements.txt

