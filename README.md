# PROJETO DATABASE
### PASSOS
- Começamos fazendo a normalização separando as colunas elencos,países,listados,diretor,rating,show,type,cast,country.
- Depois que normalizar tudo começamos a por no sql Workbench [DDL](https://github.com/cleyton123/projeto-database/blob/main/database/sql/DDLs.sql) e [DQL](https://github.com/cleyton123/projeto-database/blob/main/database/sql/DQLs.sql).
![digrama r](https://github.com/cleyton123/projeto-database/blob/main/imagens/diagramaER.png)

- Com o python conseguimos inserir os dados do csv dentro do MYSQL.
  - No arquivo [C:\Users\Cleyt\OneDrive\Área de Trabalho\projeto-database\utils\my_sql.py](https://github.com/cleyton123/projeto-database/blob/main/utils/my_sql.py), nas linhas 199 e 241 estão as DMLs de inserção no banco de dados MYSQL.
- Executando o comando ``python preencher_my_sql.py`` todos os dados do arquivo csv são inseridos no MYSQL.
- Executando o comando `python main <id>``, o Python se encarrega de realizar a busca de todas as informações do show com o id informado e o insere dentro do MongoDB.      
