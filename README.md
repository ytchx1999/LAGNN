# Local Augmentation for Graph Neural Networks

This repository contains an implementation of "Local Augmentation for Graph Neural Networks".

## Dependencies
- CUDA 10.2.89
- python 3.6.8
- pytorch 1.9.0
- pyg 2.0.3

## Usage
- To replicate the semi-supervised results, run the following script
```sh
cd Citation
bash semi.sh
```

- To replicate the full-supervised results, run the following script
```sh
cd OGB
# Pretrain: Products
python cvae_generate_products.py --latent_size 10 --pretrain_lr 1e-5 --total_iterations 10000 --batch_size 8192
# Train downstream GNNs
bash 
```
