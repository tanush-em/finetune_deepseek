# Medical DeepSeek Fine-tuning

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Hugging Face](https://img.shields.io/badge/🤗-Hugging%20Face-yellow.svg)](https://huggingface.co/)
[![unsloth](https://img.shields.io/badge/Powered%20by-unsloth-green.svg)](https://github.com/unsloth/unsloth)

Fine-tuning implementation of DeepSeek-R1-Distill-Llama-8B for medical reasoning tasks using the unsloth library for optimized training.

## Project Overview

This project fine-tunes the DeepSeek-R1-Distill-Llama-8B model specifically for medical reasoning tasks using the Medical-O1-Reasoning-SFT dataset. The implementation utilizes LoRA (Low-Rank Adaptation) for efficient parameter-efficient fine-tuning.

## Technical Details

### Base Model
- Model: `unsloth/DeepSeek-R1-Distill-Llama-8B`
- Max Sequence Length: 2048 tokens
- Quantization: 4-bit loading enabled

## Prerequisites


Required packages:
- unsloth
- transformers
- trl
- wandb
- torch
- datasets
- huggingface_hub


## Monitoring

Training progress can be monitored through Weights & Biases dashboard. Key metrics tracked include:
- Training Loss
- Learning Rate
- Training Speed (samples/second)
- GPU Memory Usage

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Hugging Face for the transformers library
- unsloth team for the optimization library
- FreedomIntelligence for the medical reasoning dataset

---

<div align="center">
Enhancing medical reasoning capabilities through optimized language model fine-tuning
</div>
