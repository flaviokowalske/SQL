# 💾 Repositório de Dicas e Snippets SQL

Este repositório tem como objetivo reunir **dicas úteis, funções SQL, snippets, comandos avançados, boas práticas e anotações** relacionadas ao uso de SQL em diversos bancos de dados, como **MySQL, PostgreSQL, SQLite, SQL Server**, entre outros.

> ✅ Ideal para consultas rápidas, estudo, apoio no trabalho e organização de conhecimento pessoal.

---

## 📂 Estrutura do Repositório

```
📁 sql-dicas/
├── README.md
├── mysql/
│   ├── funcoes-uteis.sql
│   ├── comandos-avancados.sql
│   └── boas-praticas.md
├── postgresql/
│   ├── snippets.sql
│   ├── window-functions.sql
│   └── manipulacao-json.sql
├── geral/
│   ├── modelagem-relacional.md
│   ├── normalizacao.md
│   └── cheatsheet.md
```

---

## 🧠 Conteúdos Disponíveis

### 🔧 Comandos Úteis
- Criação de banco, tabelas e índices
- Alterações com `ALTER TABLE`
- `JOINs` explicados com exemplos
- `GROUP BY`, `HAVING`, `CASE`, `COALESCE`, `IFNULL`

### 📊 Funções Populares
- Funções agregadas: `SUM()`, `AVG()`, `MAX()`, `COUNT()`
- Manipulação de strings: `CONCAT()`, `SUBSTRING()`, `REPLACE()`
- Funções de data/hora: `NOW()`, `DATEDIFF()`, `DATE_FORMAT()`
- Funções matemáticas: `ROUND()`, `CEIL()`, `FLOOR()`

### 📦 Técnicas Avançadas
- Subqueries
- Views
- CTEs (Common Table Expressions)
- Window Functions (`ROW_NUMBER()`, `RANK()`, `LEAD()`...)

### 🔄 DML e DDL
- Exemplos de `INSERT`, `UPDATE`, `DELETE`
- Transações (`BEGIN`, `COMMIT`, `ROLLBACK`)
- Constraints (`PRIMARY KEY`, `FOREIGN KEY`, `CHECK`, `UNIQUE`)

---

## 📚 Boas Práticas

- Nomeclatura de tabelas e colunas
- Uso de índices com moderação
- Cuidados com `NULL`
- Evite `SELECT *` em produção
- Prefira `EXISTS` ao invés de `IN` em grandes datasets

---

## 📌 Requisitos

- Acesso a um servidor ou SGBD local
- Ferramentas como MySQL Workbench, DBeaver, pgAdmin ou linha de comando

---

## ✍️ Contribuindo

Sinta-se livre para abrir **Issues**, propor **Pull Requests** com novas dicas ou melhorias! Qualquer sugestão é bem-vinda. Basta seguir o padrão dos diretórios e nomear os arquivos de forma clara.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Autor

**Flávio Kowalske**  
🔗 [LinkedIn](https://www.linkedin.com/in/flavio-kowalske)  
📫 Email: seuemail@dominio.com

---

## ⭐ Se achar útil...

Considere deixar uma ⭐ no repositório! Isso ajuda o projeto a crescer e alcançar mais pessoas interessadas em SQL.
