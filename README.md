# Project All For One

This project consists of a series of exercises designed to practice SQL concepts using the Northwind database.

## Installation

### With Docker

- Make sure your docker-compose is on version 1.29 or higher.
- Run the node and db services with the `docker-compose up -d` command.
- To start the container, use the command `docker exec -it all_for_one bash`.
- The database access credentials are defined in the `docker-compose.yml` file and are accessible in the container through the `MYSQL_USER` and `MYSQL_PASSWORD` environment variables.
- Install dependencies with `npm install` inside the container.
- Remember: all commands available in `package.json` must be executed inside the container.

### Without Docker

- Install dependencies with `npm install`.
- Make sure you have node installed in version 16.

## Project Requirements

The objective of the project is to develop SQL queries to find the information required by the challenges. The challenges are divided into:

- Initial Challenges: basic queries that involve manipulating data from the `products` table.
- Data Filtering Challenges: queries that involve filtering data from the `purchase_orders` table.
- Table Manipulation Challenges: data insertion, update and deletion operations in the `order_details` table.

## How to Contribute

If you find any bugs or have any suggestions for improvement, feel free to open an Issue or submit a Pull Request.

## License

This project is licensed under the MIT License.
