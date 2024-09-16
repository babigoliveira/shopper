## Descrição

1ª etapa do desafio para vaga Full-Stack da Shopper.
Esse repositório contém o código do [frontend](https://github.com/babigoliveira/shopper-frontend)
e [backend](https://github.com/babigoliveira/shopper-backend) como submódulos GIT.

## Setup

```bash
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
$  docker compose run api npm run test:e2e:cov
```
