# Natural Language to SQL using Google's Gemini Pro

This project converts natural language queries into SQL using Google's Gemini Pro and Python. It is designed to work with SQLite databases.

## Database Used

The project uses a SQLite database named `fashion_db.sqlite`. The database contains a single table, `fashion_products`, with the following columns:

- **id**: Unique identifier for each product (auto-incremented).
- **product_name**: Name of the product.
- **category**: Category of the product (e.g., Clothing, Footwear, Accessories).
- **price**: Price of the product.
- **stock_quantity**: Quantity of the product in stock.

This database is designed to simulate a simple inventory system for fashion products. You can replace it with your own database by modifying the schema and connection details.

## Main Objectives

### Natural Language to SQL Conversion
- Allow users to input natural language queries (e.g., "What is the most expensive product?") and convert them into valid SQL queries.

### Integration with Google's Gemini Pro
- Leverage Google's Gemini Pro model to generate accurate and optimized SQL queries from natural language inputs.

### Secure Query Execution
- Restrict SQL queries to `SELECT` operations only, ensuring no modifications (e.g., `INSERT`, `DELETE`, `UPDATE`) are performed on the database.

### User-Friendly Interface
- Provide a simple and intuitive interface for users to interact with the database using natural language.

### Educational and Practical Use
- Serve as a learning tool for understanding how natural language processing (NLP) can be applied to database querying.
- Demonstrate the practical use of AI models like Gemini Pro in real-world applications.


## Features
- Convert natural language queries to SQL.
- Execute SQL queries on a SQLite database.
- Secure and optimized SQL query generation.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/natural-language-to-sql-gemini.git
   cd natural-language-to-sql-gemini
