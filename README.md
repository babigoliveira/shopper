## Descrição

Desafio para vaga Full-Stack da Shopper.
Esse repositório contém o código do [frontend](https://github.com/babigoliveira/shopper-frontend)
e [backend](https://github.com/babigoliveira/shopper-backend) como submódulos GIT.

## Setup

```bash
export GEMINI_API_KEY=YOUR_KEY
git clone --recurse-submodules git@github.com:babigoliveira/shopper.git
cd shopper
docker compose up
```

| Aplicação     | URL                       |
|---------------|---------------------------|
| API           | http://localhost:3000/api |
| Mongo express | http://localhost:8081     |
| WEB App       | http://localhost:80       |

## Testes

ℹ Apenas o projeto Back-End possui testes

```bash
docker compose run api npm run test:e2e:cov
```
