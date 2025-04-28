# PneumoniaMNIST GANs — LS-GAN, WGAN, WGAN-GP Comparison

## Description
This project compares three popular GAN variants on the MedMNIST PneumoniaMNIST dataset:
- Least Squares GAN (LS-GAN)
- Wasserstein GAN (WGAN)
- Wasserstein GAN with Gradient Penalty (WGAN-GP)

We generate synthetic pneumonia X-ray images and evaluate performance quantitatively and qualitatively.

## Setup

```bash
pip install torch torchvision tensorboard medmnist torchmetrics[image] torch-fidelity scipy
```

## Evaluation Metrics
- Inception Score (IS)
- Fréchet Inception Distance (FID)
- Visual Inspection (sample images)
