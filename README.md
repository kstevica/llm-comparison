---
license: mit
task_categories:
- text-generation
language:
- en
tags:
- stories
pretty_name: LLM Comparison
size_categories:
- n<1K
---
# Fine tuning progress validation - RedPajama 3B, StableLM Alpha 7B, Open-LLaMA

This repository contains the progress of fine-tuning models: RedPajama 3B, StableLM Alpha 7B, Open-LLaMA. These models have been fine-tuned on a specific text dataset and the results of the fine-tuning process are provided in the text file included in this repository.

## Fine-Tuning Details

- **Model: RedPajama 3B, size: 3 billion parameters, method: adapter**
- **Model: StableLM Alpha 7B, size: 7 billion parameters, method: adapter**
- **Model: Open-LLaMA 7B 300B, size: 7 billion parameters (300B tokens), method: LoRA**
- **Model: Open-LLaMA 7B 300B, size: 7 billion parameters (300B tokens), method: adapter**

## Dataset

The text source used for fine-tuning these models has a size of 25MB, which has been split into 174,000 data inputs.

## Fine-Tuning Process

The fine-tuning process was conducted with the following details:

- **Epochs:** 1
- **Validation Frequency:** Every 1% of the training data
- **Training Data:** 174,000 data inputs

## Acknowledgments #1

I would like to acknowledge @stabilityai, @togethercompute and OpenLM Research for providing the base models. Their groundbreaking work in the field of natural language processing has made projects like this possible.

## Acknowledgments #2

I would like to acknowledge @LightningAI for providing the lit-parrot fine-tuning framework.

## Disclaimer

There might be NSFW results in the results.

## License

This repository and the fine-tuned models are licensed under the [MIT License](LICENSE). Feel free to modify and use them according to the terms of the license.