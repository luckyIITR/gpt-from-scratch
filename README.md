# gpt-from-scratch

GPT From Scratch

This project builds a simple GPT-style language model from scratch using PyTorch.
It trains on a character-level dataset (Tiny Shakespeare) with a minimal Transformer architecture, including self-attention, multi-head attention, feedforward layers, and layer normalization.

How to run

1.	Install requirements:

```python
pip install torch
```


2.	Run the training script:
```python
python train.py
```

3.	After training, the model will generate sample text.

Features
- Character-level tokenizer
- Basic Transformer with multi-head self-attention
- Small architecture: 4 layers, 4 heads, 64-dimensional embeddings
- Optimizer: AdamW
- Device support: CPU or CUDA