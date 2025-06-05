
## Local LLM - Ollama

Steps to run local LLM for yourself and work with it.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


## Steps to run

1. Install Docker based on your OS.

2. Install Ollama
```bash
    curl -fsSL https://ollama.com/install.sh | sh
```

3. Clone the project
```bash
  git clone https://github.com/thisissoroush/Ollama.git
```

4. Go to the project directory

```bash
  cd Ollama
```

5. Excute the compose File
```bash
  docker compose up -d
```

6. Ollama Serve
```bash
  docker exec -it ollama ollama serve
```
7. Pull the model(or models)
```bash
  docker exec -it ollama ollama pull [YourModel(e.g. qwen3:235b)]
```

8. Check Url's
```bash
    http://localhost:11434/v1/models --> List of models on ollama
    http://localhost:8080 --> open web ui for ollama
```

## Author

- [@Soroush Nasiri](https://www.github.com/Thisissoroush)

