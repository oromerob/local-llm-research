# Local (LLM) Deep Research

## Basic Ollama & web UI

### 1. Start Services
```shell
dccd up -d
```
Where `dccd` is configured in the shell profile (or similar) as an alias:
```
# .zshrc
alias dccd="docker compose -f docker-compose.dev.yml --env-file .env"
```

### 2. Install DeepSeek r1

```shell
dccd exec ollama ollama run deepseek-r1:32b
```

### 3. Access DeepSeek chat interface

Open your browser here -> [http://localhost:7869/](http://localhost:7869/)
