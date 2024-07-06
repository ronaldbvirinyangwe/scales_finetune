# Llama 3 8B Fine-Tuning - Scales Shona Ai


Many thanks to Unsloth for their oustanding work on quantization and LoRA! Here is <a href="https://colab.research.google.com/drive/135ced7oHytdxu3N2DNe1Z0kqjyYIkDXp?usp=sharing">Unsloth's original work</a>.

## Installation

If you don't have Ollama installed, you may want to install that locally before starting the demo, but it's not required. You can still follow along.

### macOS

[Download](https://ollama.com/download/Ollama-darwin.zip)

### Windows preview

[Download](https://ollama.com/download/OllamaSetup.exe)

### Linux

```
curl -fsSL https://ollama.com/install.sh | sh
```

[Manual install instructions](https://github.com/ollama/ollama/blob/main/docs/linux.md)

### Docker

The official [Ollama Docker image](https://hub.docker.com/r/ollama/ollama) `ollama/ollama` is available on Docker Hub.

### Libraries

- [ollama-python](https://github.com/ollama/ollama-python)
- [ollama-js](https://github.com/ollama/ollama-js)

### Quickstart

To run and chat with [Llama 3](https://ollama.com/library/llama3):

```
ollama run llama3
```
