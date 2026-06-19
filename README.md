# Transformer From Scratch (Attention Is All You Need)

A complete implementation of the original Transformer architecture proposed in the paper "Attention Is All You Need" using TensorFlow, built entirely from scratch without using TensorFlow's built-in MultiHeadAttention layer.

## Features

- Positional Encoding
- Padding Mask
- Look-Ahead Mask
- Scaled Dot-Product Attention
- Multi-Head Attention
- Encoder Layer
- Encoder Stack
- Decoder Layer
- Decoder Stack
- Full Transformer Architecture
- Custom Learning Rate Scheduler
- Training Pipeline
- Greedy Decoding

## Transformer Architecture

Input
↓
Embedding + Positional Encoding
↓
N × Encoder Layers
↓
Encoder Output
↓
N × Decoder Layers
↓
Linear Layer
↓
Softmax

## Project Structure

Transformer-From-Scratch/
├── Transformer_From_Scratch.ipynb
├── README.md

