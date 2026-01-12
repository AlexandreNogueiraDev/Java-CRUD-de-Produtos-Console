# Java CRUD de Produtos (Console)

Projeto desenvolvido em **Java**, utilizando **MySQL**, com o objetivo de praticar a integração entre aplicação Java e banco de dados, aplicando os conceitos de **CRUD (Create, Read, Update, Delete)** em um sistema de console.

## 📌 Funcionalidades
- Cadastrar produtos no banco de dados
- Listar produtos cadastrados
- Atualizar informações de um produto
- Remover produtos
- Conexão com banco de dados MySQL via JDBC

## 🛠️ Tecnologias Utilizadas
- Java
- MySQL
- JDBC
- SQL

## 📂 Estrutura do Projeto
- Camada de conexão com o banco de dados
- Classe de entidade (Produto)
- Operações CRUD
- Menu interativo via console

## 🗄️ Banco de Dados
O projeto utiliza um banco de dados MySQL com uma tabela de produtos.

Exemplo de estrutura da tabela:

```sql
CREATE TABLE produtos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100),
    preco DECIMAL(10,2),
    quantidade INT
);
