# Multicritérios de Análise de Desempenho Acadêmico

## Descrição do Projeto
Este projeto implementa um sistema para gerenciar o empréstimo de publicações acadêmicas para alunos, utilizando Java, JPA (Java Persistence API) e o framework Maven. O projeto inclui mapeamento das entidades do banco de dados, criação de DAOs (Data Access Objects) e testes unitários para operações CRUD (Create, Read, Update, Delete).

## Estrutura do Projeto
O projeto está estruturado conforme abaixo:

- `src/main/java/`
  - `Aluno.java` - Classe que mapeia a entidade Aluno.
  - `Publicacao.java` - Classe que mapeia a entidade Publicação.
  - `Emprestimo.java` - Classe que mapeia a entidade Empréstimo.
  - `EmprestimoDAO.java` - Classe DAO que realiza operações CRUD para a entidade Empréstimo.
  
- `src/test/java/`
  - `EmprestimoDAOTest.java` - Classe de teste para o DAO de Empréstimo, com métodos de teste para as operações de CRUD.

## Requisitos do Sistema
- Java 11 ou superior
- Maven 3.6 ou superior
- Banco de dados relacional (MySQL, PostgreSQL, etc.)
- JUnit 5 para testes unitários

## Como Executar o Projeto
1. **Clone o Repositório**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
