# Local (LLM) Deep Research

## 0. Basic Ollama & web UI

### Start Services
```shell
dccd up -d
```
Where `dccd` is configured in the shell profile (or similar) as an alias:
```
# .zshrc
alias dccd="docker compose -f docker-compose.dev.yml --env-file .env"
```

## 1. Install DeepSeek r1

```shell
dccd exec ollama ollama run deepseek-r1:32b
```
