# Evolution API

Este projeto sobe o Evolution API utilizando Docker Compose.

## Requisitos

- Docker
- Docker Compose

## Como Iniciar

1. Clone o repositório:
```bash
git clone https://github.com/matheuspdias/evolution-api.git
cd evolution-api
```

2. Configure as variáveis de ambiente:
```bash
cp .env.example .env
```

3. Inicie os containers:
```bash
docker-compose up -d
```

## Acesso

A API estará disponível em: http://localhost:8082

## Serviços

O projeto sobe os seguintes serviços:

- **Evolution API**: Porta 8082
- **PostgreSQL**: Banco de dados
- **Redis**: Cache (porta 6380)

## API Key Padrão

A API Key padrão configurada é: `429683C4C977415CAAFCCE10F7D57E11`

Altere no arquivo `.env` a variável `AUTHENTICATION_API_KEY` para uma chave personalizada.
