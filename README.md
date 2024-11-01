# AiConnect 

Este projeto é uma API para gerenciar clientes e pedidos, com automação de deploy usando Azure DevOps. Ele foi feito para demonstrar o uso de pipelines CI/CD e boas práticas DevOps, facilitando o deploy e a manutenção.

## O que este projeto faz?

- Cria e gerencia dados de clientes e pedidos usando uma API.
- Inclui duas tabelas principais no banco de dados: `Clientes` e `Pedidos`.
- Implementa automação de deploy e atualizações pelo Azure.

## Tecnologias

- **C#** e **.NET** para o código
- **Azure SQL Database** para o banco de dados
- **Azure DevOps** para CI/CD (pipeline)
- **Azure App Service** para hospedar a aplicação

## Como Instalar

1. Clone o repositório:

   ```bash
   git clone https://github.com/260904camila/AiConnect-Sprint3.git
   cd AiConnect-Sprint3
   ```

2. Instale as dependências:

   ```bash
   dotnet restore
   ```

3. Rode a aplicação:

   ```bash
   dotnet run
   ```

## Configuração

- **Banco de Dados**: Rode o script SQL em `sql-scripts/setup.sql` no Azure SQL Database para configurar as tabelas.
- **Pipeline CI/CD**: Importe o arquivo `pipeline/azure-pipelines.yml` no Azure DevOps para configurar o pipeline.

## Como Usar a API

Principais endpoints disponíveis:

- `GET /api/clientes` - Lista todos os clientes
- `POST /api/clientes` - Adiciona um cliente
- `GET /api/pedidos` - Lista todos os pedidos
- `POST /api/pedidos` - Adiciona um pedido


