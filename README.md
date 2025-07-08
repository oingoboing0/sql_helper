# sql_helper
Fine-tuning open-source LLM using LoRA with Unsloth, then deploys them locally via Ollama locally. Includes adapter training, model export, and custom Modelfile setup for low-resource inference.

this notebook saves your llama3 finetuning to your google drive for easy downloading, put the gguf file in a folder with ollama running then run 

FROM <gguf filename>

SYSYTEM "system prompt here"


and boom locally hosted LLM that is good at sql
