Instalar o Docker.
Dentro do diretório onde está o docker-compose.yml, e com o Docker rodando,
executar o comando:
> docker-compose up -d

Instalar o Prisma:
> npm install -D prisma

Instalar o Client do Prisma:
> npm install @prisma/client

Inicializar o Prisma:
> npx prisma init

Executar a migration:
> npx prisma migrate dev --name init

Para iniciar o prisma studio:
> npx prisma studio

Popular o banco de Dados:
> npx prisma db seed

Teste de Conexão:
> npx tsx src/testConnection.ts

npm run dev 
