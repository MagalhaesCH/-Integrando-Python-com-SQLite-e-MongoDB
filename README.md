# -Integrando-Python-com-SQLite-e-MongoDB
Projeto para DIO.me

Plano
Configurar o ambiente:

Instalar bibliotecas necessárias (sqlite3 e pymongo).
Criar banco de dados SQLite:

Conectar ao banco de dados SQLite.
Criar uma tabela e inserir alguns dados.
Migrar dados do SQLite para MongoDB:

Conectar ao banco de dados MongoDB.
Ler dados do SQLite.
Inserir dados no MongoDB.

# Código no diretório

Explicação do Código
Criar e Popular Banco de Dados SQLite:

A função create_sqlite_db conecta ao banco de dados SQLite example.db (cria se não existir).
Cria uma tabela chamada users se não existir.
Insere três registros na tabela users.
Migrar Dados do SQLite para MongoDB:

A função migrate_sqlite_to_mongo conecta ao banco de dados SQLite e lê todos os registros da tabela users.
Conecta ao MongoDB e insere os registros lidos do SQLite na coleção users do banco de dados example_db.

