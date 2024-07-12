# Sistema de Usuários e Departamentos - API REST

Este projeto é uma API REST desenvolvida para gerenciar usuários e departamentos. Ele inclui funcionalidades básicas como busca, inserção e consulta de dados. O sistema foi criado utilizando Springboot, JPA e H2 para garantir um desenvolvimento eficiente e fácil manutenção.

## Funcionalidades

- **Buscar todos os usuários**: Recupera a lista completa de usuários cadastrados no sistema.
- **Buscar um usuário pelo seu ID**: Permite a busca de um usuário específico utilizando seu ID único.
- **Inserir um novo usuário**: Adiciona um novo usuário ao banco de dados.

## Configuração do Banco de Dados H2

O banco de dados H2 é configurado para rodar em memória, tornando o desenvolvimento e testes mais rápidos e fáceis. A configuração pode ser encontrada no arquivo `application.properties`.

## Endpoints da API REST

### Usuários

- **GET /usuarios**: Busca todos os usuários.
- **GET /usuarios/{id}**: Busca um usuário específico pelo ID.
- **POST /usuarios**: Insere um novo usuário.

### Departamentos

- Em breve...

## Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/lacatye/api-rest-java.git]
