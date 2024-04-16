# Projeto de Gerenciamento de Bolsistas e Pagamentos

Este projeto é um sistema de gerenciamento de bolsistas.

## Comandos Maven

Para compilar o projeto, execute o seguinte comando:

- mvn clean install

- mvn test

## JAVA 17

## Endpoints da API

- **GET /api/bolsistas/findAll**: Retorna todos os bolsistas cadastrados.
- **POST /api/bolsistas/alterar-bolsista**: Altera os dados de um bolsista.
- **PUT /api/bolsistas/insert-bolsista**: Insere um novo bolsista.
- **PUT /api/bolsistas/desativar-bolsista/{id}**: Desativa um bolsista pelo ID.

## Exemplo de JSON para Bolsista / Pagamento

```json
{
    "id": 4,
    "nomeCompleto": "Willyan Fernando 2",
    "tipoIdentificador": 1,
    "numeroIdentificador": "12345678",
    "dataCadastro": "2024-04-15",
    "codigoBanco": "005",
    "numeroAgencia": "1415",
    "numeroConta": "24680-1",
    "status": null
}
