## 🌐 [Versão em Português do README](README.md)

# Course: Database Administration - Fundação Bradesco

This repository contains the files and materials used in the **Database Administration** course from Fundação Bradesco. The course covers the creation, management, backup, and maintenance of databases using SQL Server. Practical examples include database creation, data import and export, as well as backup and recovery operations.

## 🔨 Course Features

- The course demonstrates SQL Server operations, including creating and managing a fictional database for a movie rental business.
- Data is structured in several tables (clients, movies, orders, etc.), with examples of importing data from Excel and performing backup and recovery operations.

## ✔️ Techniques and Technologies Used
- **SQL Server**: For database creation and management.
- **SSMS (SQL Server Management Studio)**: For administrative operations on the database.
- **T-SQL**: SQL language used for database manipulation.
- **Excel**: For importing data into tables.
- **Backup and Recovery**: Performing full and differential backups using SSMS.

## 📁 Project Structure
- **Archives/**
    - `LOCADORA_DADOS.mdf`: SQL Server database data file.
    - `LOCADORA_LOG.ldf`: SQL Server transaction log file.
    - `tbl_clientes.xls`: Excel file for the clients table.
    - `tbl_clientes.zip`: Compressed version of the clients table.
    - `tbl_detalhesdopedido.xls`: Excel file for order details.
    - `tbl_detalhesdopedido.zip`: Compressed version of the order details table.
    - `tbl_filmes.xls`: Excel file for movies table.
    - `tbl_filmes.zip`: Compressed version of the movies table.
    - `tbl_genero.xls`: Excel file for movie genres table.
    - `tbl_genero.zip`: Compressed version of the genres table.
    - `tbl_pedidos.xls`: Excel file for orders table.
    - `tbl_pedidos.zip`: Compressed version of the orders table.

- **Documentation/**
    - `adm_bd - Database Administration.pdf`: Course manual.
    - `tela_*.pdf`: Detailed guides for SQL Server operations, such as backup, data import, and more.

## 🛠️ Running the Project Locally

To start working with the database, follow these steps:

1. **Ensure that SQL Server and SSMS are installed**:
    - You need [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) to run the database locally.
    - [SSMS](https://aka.ms/ssmsfullsetup) should be used to manage the database.

2. **Clone the Repository**:
    - Copy the repository URL and run the command below in your terminal:

      ```bash
      git clone <REPOSITORY_URL>
      ```

3. **Import the Database**:
    - In SSMS, connect to your SQL server.
    - Attach the `LOCADORA_DADOS.mdf` data file and the `LOCADORA_LOG.ldf` log file.

4. **Import Tables**:
    - Use the Excel files to import data into the tables via SSMS or T-SQL commands as outlined in the course tutorials.

5. **Backup Operations**:
    - Follow the instructions from the course to perform full and differential backups using SSMS.

## 🌐 Deploy

To deploy in a production environment, you can use the backup and recovery methods taught during the course. Deployment involves migrating the database to a production server and configuring automatic backups, monitoring, and periodic maintenance.

