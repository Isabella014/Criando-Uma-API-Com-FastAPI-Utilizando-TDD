# Products API

Este projeto é uma API para gerenciar produtos, construída com [FastAPI](https://fastapi.tiangolo.com/) e [MongoDB](https://www.mongodb.com/).

## Endpoints

### Criar Produto

- **URL:** `/`
- **Método:** `POST`
- **Status Code de Sucesso:** `201 Created`
- **Request Body:**
  ```json
  {
    "name": "Nome do Produto",
    "description": "Descrição do Produto",
    "price": 100.0
  }
- Response Body:
```json
Copiar código
{
  "id": "UUID",
  "name": "Nome do Produto",
  "description": "Descrição do Produto",
  "price": 100.0,
  "created_at": "Data de Criação",
  "updated_at": "Data de Atualização"
}
