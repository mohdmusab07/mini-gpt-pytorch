# mini-gpt-pytorch
Decoder-only GPT language model built from scratch in PyTorch with causal self-attention, multi-head attention, LayerNorm, residual connections, and autoregressive text generation.

# Character-Level GPT from Scratch (PyTorch)

An end-to-end implementation of a decoder-only, autoregressive Transformer language model built from scratch in PyTorch. This project was created as a learning implementation to understand the internal mechanics of GPT, including causal self-attention, multi-head attention, residual connections, LayerNorm, and text generation.

## Features

- Character-level tokenizer
- Learnable token embeddings
- Learnable positional embeddings
- Causal masked self-attention
- Multi-head attention
- Feed-forward network (4× expansion)
- Pre-LayerNorm residual blocks
- Autoregressive character generation
- Training on Tiny Shakespeare

## Architecture

Input IDs
      │
Token + Position Embeddings
      │
Transformer Block × N
      │
Final LayerNorm
      │
Linear Language Modeling Head
      │
Next Character Prediction

## Example Output

KING:
Thou art more gentle than the winds of night...

## Acknowledgements

This implementation was built as an educational project inspired by:

- **Andrej Karpathy** — *Let's Build GPT: From Scratch*
- **Vaswani et al. (2017)** — *Attention Is All You Need*

The architecture and concepts originate from these works; this repository is my own PyTorch implementation created for learning and experimentation.
