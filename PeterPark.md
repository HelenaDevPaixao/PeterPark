# PeterPark

Uma API simples para realizar operações CRUD (Criar, Ler, Atualizar, Excluir) em recursos de carros.

## Endpoints

### 1. Criar Carro

- **URL:** `/api/cars`
- **Método:** `POST`
- **Descrição:** Cria um novo carro.
- **Corpo da Requisição:**
  ```json
  {
    "modelo": "Sedan",
    "cor": "Vermelho",
    "placa": "ABC-1234",
    "descricao": "Semi novo."
  }

