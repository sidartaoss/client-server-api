## Desafio Client-Server-API

1. Abrir o terminal na raiz do projeto;

2. Subir o servidor, executando:

```
go run server.go
```

3. Ao subir o servidor, é gerado, no diretório raiz, o arquivo **test.db** do SQLite. A cada vez que se sobe o servidor, o banco de dados é iniciado com a tabela **cotacoes** vazia;

4. Abrir um novo terminal e mover-se para o diretório **client**;

5. Executar o comando:

```
go run client.go
```

6. É gerado o arquivo **cotacao.txt** no diretório **client**;

7. Pode-se conferir o registro da cotação recebida no diretório raiz:

```sh
sqlite3 test.db
select * from cotacoes;
```
