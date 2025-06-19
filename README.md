# Transformer PEFT Sentiment Classification

This project implements and compares four fine-tuning strategies for transformer-based models (RoBERTa-Base) on a small-scale sentiment classification task using the IMDb dataset. The comparison focuses on evaluating accuracy, number of trainable parameters, training time, and GPU memory usage across methods, including full fine-tuning and parameter-efficient fine-tuning (PEFT).

## Objectives

- Apply and compare Full Fine-Tuning, LoRA, QLoRA, and IA3 Adapters (PEFT techniques) on RoBERTa-Base.
- Measure performance trade-offs in terms of accuracy, efficiency, and resource usage.
- Visualize and analyze results to provide recommendations for each method's best use case.

## Methods Compared

**Full Fine-Tuning** — Fine-tune all model parameters  
**LoRA** — Low-rank adaptation fine-tuning  
**QLoRA** — Quantized LoRA (4-bit quantization + LoRA adapters)  
**IA3 (Adapter Tuning)** — Insert IA3 adapters and fine-tune only adapters  

## Dataset

- **IMDb Sentiment Classification**  
- 5,000 samples (3,000 train / 2,000 test)  
- Binary labels: positive / negative  
