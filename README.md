# Fake Shop
Processo de CI CD criado conforme abaixo

CI

Realiza a construção da imagem passando o codigo realizando o build e enviando para do Docker Hub realizando o incremento da versão V+1 e latest

CD

Realiza a publicação da imagem criada e publicada no Docker Hub ao kubernets passando a autenticação do kubeconfig realizando o deploy atraves do arquivo deployment.yaml


## Variável de Ambiente
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.


