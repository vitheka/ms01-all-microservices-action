[![Continuos Integration with GitHub](https://github.com/vitheka/ms01-all-microservices-action/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/vitheka/ms01-all-microservices-action/actions/workflows/docker-publish.yml)

# Microserviço de Livros

Este é um microserviço de livros que mantém os preços dos livros em dólar (USD). O principal objetivo deste serviço é fornecer um método que aceita o identificador do livro (ID) e a sigla da moeda de câmbio (por exemplo, BRL) e retorna o preço do livro convertido para a moeda solicitada.

## Como rodar o projeto

1. Clone o repositório com todos os submódulos:
```bash
git clone --recursive git@github.com:vitheka/ms01-all-microservices-action.git
```

2. Navegue até a pasta do projeto::
```bash
cd githubActions
```
3. Inicie todos os serviços usando o Docker Compose: 
```bash
docker-compose up -d
```
Este comando irá baixar todas as imagens necessárias do Docker Hub e iniciar os serviços.


