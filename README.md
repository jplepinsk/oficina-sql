# Oficina SQL

Plataforma de estudo de SQL para **MySQL 8.0 ou superior**, em português, para turmas de banco de dados.

## Conteúdo

| Módulo | Assuntos |
|---|---|
| Apoio | `SELECT VERSION()`, `SHOW`, `USE`, `DESC`, `SHOW CREATE TABLE`, `SHOW WARNINGS` |
| DDL | `CREATE`, `ALTER`, `DROP`, `TRUNCATE`, tipos de dados, restrições e chaves estrangeiras |
| DML | `INSERT`, `UPDATE`, `DELETE` e erros de integridade |
| DQL | `SELECT`, filtros com `WHERE`, funções, `GROUP BY`/`HAVING` e `JOIN` |
| DCL | Usuários, `GRANT`, `REVOKE` e papéis (básico) |
| TCL | `START TRANSACTION`, `COMMIT`, `ROLLBACK`, `SAVEPOINT` (básico) |
| Avançados | `INDEX`, `VIEW`, `TRIGGER`, `PROCEDURE`, `FUNCTION` |

Cada lição tem objetivo, exemplo para copiar e exercício com resposta. Os exemplos usam o banco de prática `biblioteca`, cujo script está na própria plataforma.

O projeto final, **Sistema Barbearia**, traz o MER, o dicionário de dados, seis etapas avaliadas (100 pontos), os dados para carga e um verificador que confere a estrutura do script colado pelo aluno.

## Como usar

Abra `index.html` no navegador. Não há instalação nem servidor: os comandos são executados pelo aluno no MySQL Workbench. O progresso das lições fica salvo no navegador.

Para publicar no GitHub Pages: *Settings → Pages → Deploy from a branch → `main` / root*.

## Arquivos

- `index.html`: plataforma completa (conteúdo, estilos e scripts)
- `img/`: diagramas conceitual e lógico do MER da barbearia

O gabarito do projeto não faz parte deste repositório.
