Comandos do Prisma:

Iniciar e escolher qual a tecnologia

# npx prisma init --datasource-provider SQLite

Gerar a tabela

# npx prisma migrate dev

Abrir o prisma no navegador

# npx prisma studio

Comando para rodar o Docker

# docker run --name mysql -e MYSQL_ROOT_PASSWORD=docker -p 3306:3306 mysql:latest

Comando para iniciar o container

# docker start mysql

Comando para parar o container

# docker stop mysql

Comando para enviar o banco do prisma para o servidor

# npx prisma db push
