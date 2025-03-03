# Hacking Quepid to work with Ollama 

or any other llm compatible with OpenAI completion API

```
docker compose exec ollama ollama pull llama2
docker compose run quepid bin/rake db:migrate
docker compose run quepid bin/rake db:seed
```