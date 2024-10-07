# LLM Finetuning and Use Case Demonstrations with Unsloth and Ollama

## Overview
This project involves recording video demonstrations of various use cases of fine-tuning and continued pretraining of large language models (LLMs) using open-source weights. The fine-tuned models are exported to the Ollama framework for inference. The assignment covers multiple tasks, such as fine-tuning, chat model templates, reward modeling, continued pretraining, and exporting models for inference. Each section below describes a unique use case, the models used, and the processes demonstrated.

## Video Demonstrations
Each section of the assignment has a corresponding video that clearly explains:
1. How the finetuning/pretraining works.
2. Input format and dataset used.
3. The type of task performed for each model.

## Use Cases

### a) Fine-Tuning Use Cases
We fine-tune the following LLMs for four different tasks (e.g., coding, chat-based tasks):
- **Llama 3.1 (8B)**
- **Mistral NeMo (12B)**
- **Gemma 2 (9B)**
- **TinyLlama (1B)**

The demonstrations showcase:
- Various chat model templates for each unique task.
- Step-by-step walkthrough on how to fine-tune each model using input data formats.
- Video links explain these models in a coding, chat, and conversational context.

[Reference: Unsloth Fine-Tuning with Ollama](https://sarinsuriyakoon.medium.com/unsloth-lora-with-ollama-lightweight-solution-to-full-cycle-llm-development-edadb6d9e0f0)

### b) Continued Pretraining Use Case
This section demonstrates how to use Unsloth AI to make an LLM learn a new language. We use the [Unsloth documentation on continued pretraining](https://docs.unsloth.ai/basics/continued-pretraining).

The model is pretrained to enhance its multilingual capabilities, showing how the training loop works with new datasets and language-specific data.

### c) Chat Templates for Multiple Use Cases
In this section, we demonstrate chat templates for:
- **Classification tasks**
- **Conversational chat**
- **Extending max context size for TinyLlama**
- **Fine-tuning across multiple datasets**

Each video showcases how to apply these templates for specific NLP tasks using various fine-tuning methods.

### d) Reward Modeling with ORPO and DPO
Here, we fine-tune models using both:
- **ORPO (Optimized Reward Policy Optimization)**, and
- **DPO (Deterministic Policy Optimization)**

[Reference: Unsloth Reward Modeling Documentation](https://docs.unsloth.ai/basics/reward-modelling-dpo-and-orpo)

The videos explain how to optimize the model’s performance by rewarding preferred behaviors and punishing undesired actions.

### e) Continued Fine-Tuning from a Custom Checkpoint
This video demonstrates how to resume fine-tuning from a custom model checkpoint, improving the model's performance for a specific use case by starting from previously learned parameters.

### f) Mental Health Chatbot Development (Fine-tuning Phi-3)
In this section, we use **Microsoft Phi-3** with Unsloth to fine-tune a model for mental health chatbot development. 

[Reference: Fine-tuning Phi-3 for Mental Health](https://medium.com/@mauryaanoop3/fine-tuning-microsoft-phi3-with-unsloth-for-mental-health-chatbot-development-ddea4e0c46e7)

The chatbot is designed to assist users with mental health inquiries by generating empathetic responses based on user input.

### g) Exporting Fine-Tuned Models to Ollama
In the final section, we use Unsloth to fine-tune a model (e.g., **Llama 3**) and export it to Ollama for inference. The demonstration covers:
- Steps to fine-tune the model.
- How to export the fine-tuned model to Ollama.
- Running inference on the exported model.

[Reference: Exporting Fine-tuned Models to Ollama](https://docs.unsloth.ai/tutorials/how-to-finetune-llama-3-and-export-to-ollama)



