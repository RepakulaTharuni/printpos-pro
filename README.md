# PrintPOS Pro

PrintPOS Pro is an integrated printer and Point of Sale (POS) system tailored for the medical field to streamline prescription generation and billing. This README file provides steps to set up the application, including the frontend, backend, database, and printer configuration.

## Prerequisites

Node.js and npm (for frontend)
Java (for backend with Spring Boot)
Maven or Gradle (for backend dependency management)
MySQL (for database)
POS Printer (configured to work with the application)

## Frontend Setup

1. Clone the repository:
```bash
    git clone https://github.com/RepakulaTharuni/printpos-pro.git ```
    

2. Navigate to the frontend directory:
```bash
    cd printpos-pro/frontend ```
    

3. Install dependencies:
```bash
    npm install ```
    

4. Start the development server:
```bash
    npm start ```
    
This command will start the frontend on a development server, usually accessible at http://localhost:3000.

## Backend Setup

1. Clone the repository :

   ```bash
    git clone https://github.com/RepakulaTharuni/printpos-pro.git ```
    

2. Navigate to the backend directory:
```bash
    cd printpos-pro/backend```
    

3. Install dependencies (using Maven or Gradle):

    If using Maven:
```bash
    mvn install```
    

4. Run the backend server:
```bash
    mvn spring-boot:run```
    

    This command will start the backend Spring Boot application on http://localhost:8080.


## Database Setup

1. Install MySQL and create a new database:
```bash
    sql
    CREATE DATABASE printposdb;```
    

2. Import the database schema:

    Locate the schema.sql file in the database folder and import it into your MySQL database.

3. Configure the database connection:

    Open the application.properties file in the backend configuration directory and update the MySQL connection details as needed.

## Printer Setup

Ensure that the POS printer is connected and configured to work with PrintPOS Pro. Refer to your printer’s documentation for specific setup instructions.

## Contributing

We welcome contributions to improve PrintPOS Pro. Please follow the guidelines in CONTRIBUTING.md if available.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
