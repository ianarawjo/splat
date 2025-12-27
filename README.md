
### Ollama

To call Ollama from localhost, you *must* enable CORS policy on your running Ollama instance. Follow these instructions: https://objectgraph.com/blog/ollama-cors/

For MacOS, what worked for us was running: 

```bash
launchctl setenv OLLAMA_ORIGINS "*"
```

in the terminal, then restarting Ollama and serving it via `ollama serve`. 