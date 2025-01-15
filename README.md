# Chatwoot - Integração com API Oficial do WhatsApp

Este repositório configura uma instância do Chatwoot para testar a API oficial do WhatsApp (WhatsApp Cloud API) da Meta. O objetivo é integrar e testar a comunicação entre o Chatwoot e a API do WhatsApp em um ambiente local.

## Requisitos
- Docker
- Ngrok para simular o http

## Comandos
Antes de mais nada renomeie o .env.example para .env
Troque as variaveis pelas suas.

Para rodar as migrations e seeds do banco
- docker compose run --rm rails bundle exec rails db:chatwoot_prepare

Para iniciar a stack 
- docker compose up -d

## Links

- http://localhost:3000

## Melhorias
Traefik Proxy para ssl em produção