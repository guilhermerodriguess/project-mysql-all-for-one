# Projeto All For One

Este projeto consiste em uma série de exercícios destinados a prática dos conceitos de SQL, utilizando o banco de dados Northwind.

## Instalação

### Com Docker

- Certifique-se de que seu docker-compose está na versão 1.29 ou superior.
- Execute os serviços node e db com o comando `docker-compose up -d`.
- Para iniciar o container, utilize o comando `docker exec -it all_for_one bash`.
- As credenciais de acesso ao banco de dados estão definidas no arquivo `docker-compose.yml` e são acessíveis no container através das variáveis de ambiente `MYSQL_USER` e `MYSQL_PASSWORD`.
- Instale as dependências com `npm install` dentro do container.
- Lembre-se: todos os comandos disponíveis no `package.json` devem ser executados dentro do container.

### Sem Docker

- Instale as dependências com `npm install`.
- Certifique-se de que tem o node instalado na versão 16.

## Requisitos do Projeto

O objetivo do projeto é desenvolver queries SQL para encontrar as informações requisitadas pelos desafios. Os desafios estão divididos em:

- Desafios Iniciais: queries básicas que envolvem a manipulação dos dados da tabela `products`.
- Desafios de Filtragem de Dados: queries que envolvem a filtragem dos dados da tabela `purchase_orders`.
- Desafios de Manipulação de Tabelas: operações de inserção, atualização e exclusão de dados na tabela `order_details`.

## Como Contribuir

Se encontrar algum erro ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma Issue ou enviar um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT.
