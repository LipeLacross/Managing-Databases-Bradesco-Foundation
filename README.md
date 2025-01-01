## 🌐 [English Version of README](README_EN.md)

# Curso: Administrando Banco de Dados - Fundação Bradesco

Este repositório contém os arquivos e materiais utilizados no curso **Administrando Banco de Dados** da Fundação Bradesco. O curso aborda a criação, gerenciamento, backup e manutenção de bancos de dados utilizando o SQL Server. Os exemplos práticos cobrem a criação de bancos de dados, importação e exportação de dados, bem como operações de backup e recuperação.

## 🔨 Funcionalidades do Curso

- O curso demonstra operações no SQL Server, incluindo a criação e manipulação de um banco de dados fictício para uma locadora de filmes.
- Os dados são estruturados em várias tabelas (clientes, filmes, pedidos, etc.), com exemplos de importação de dados do Excel e operações de backup e recuperação.

## ✔️ Técnicas e Tecnologias Utilizadas
- **SQL Server**: Para criação e gerenciamento do banco de dados.
- **SSMS (SQL Server Management Studio)**: Para operações administrativas de banco de dados.
- **T-SQL**: Linguagem SQL utilizada para manipulação do banco de dados.
- **Excel**: Para importar dados das tabelas.
- **Backup e Recuperação**: Execução de backups completos e diferenciais utilizando SSMS.

## 📁 Estrutura do Projeto
- **Archives/**
    - `LOCADORA_DADOS.mdf`: Arquivo de dados do banco de dados SQL Server.
    - `LOCADORA_LOG.ldf`: Arquivo de log de transações do banco de dados.
    - `tbl_clientes.xls`: Tabela de clientes em formato Excel.
    - `tbl_clientes.zip`: Versão compactada da tabela de clientes.
    - `tbl_detalhesdopedido.xls`: Tabela de detalhes dos pedidos.
    - `tbl_detalhesdopedido.zip`: Versão compactada da tabela de detalhes dos pedidos.
    - `tbl_filmes.xls`: Tabela de filmes.
    - `tbl_filmes.zip`: Versão compactada da tabela de filmes.
    - `tbl_genero.xls`: Tabela de gêneros de filmes.
    - `tbl_genero.zip`: Versão compactada da tabela de gêneros.
    - `tbl_pedidos.xls`: Tabela de pedidos.
    - `tbl_pedidos.zip`: Versão compactada da tabela de pedidos.

- **Documentation/**
    - `adm_bd - Administrando Banco de Dados.pdf`: Manual do curso.
    - `tela_*.pdf`: Guias detalhados para operações de SQL Server, como backup, importação de dados, e muito mais.

## 🛠️ Abrir e Rodar o Projeto

Para iniciar as operações com o banco de dados, siga os passos abaixo:

1. **Certifique-se de que o SQL Server e o SSMS estão instalados**:
    - O [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) é necessário para rodar o banco de dados localmente.
    - O [SSMS](https://aka.ms/ssmsfullsetup) deve ser utilizado para a administração do banco de dados.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Importe o Banco de Dados**:
    - No SSMS, conecte-se ao seu servidor SQL.
    - Anexe o arquivo `LOCADORA_DADOS.mdf` e o arquivo de log `LOCADORA_LOG.ldf`.

4. **Importação das Tabelas**:
    - Utilize os arquivos Excel para importar os dados nas tabelas usando SSMS ou comandos T-SQL, conforme os tutoriais do curso.

5. **Operações de Backup**:
    - Siga as orientações no curso para criar backups completos e diferenciais utilizando o SSMS.

## 🌐 Deploy

Para realizar o deploy em um ambiente de produção, você pode utilizar os métodos de backup e recuperação ensinados durante o curso. O deploy envolve a migração do banco de dados para um servidor de produção e a configuração de backups automáticos, monitoramento e manutenção periódica.

