# Hacking Quepid to work with Ollama 

or any other llm compatible with OpenAI completion API

```
docker compose run quepid bin/rake db:migrate
docker compose run quepid bin/rake db:seed
docker compose up
docker compose exec ollama ollama pull llama2
```

after that you can open quepid running at http://localhost:3000/
