# Criação de API e documentação
## Utilizaremos o Swagger para criar e documentar uma API RESTful. O Swagger é uma ferramenta poderosa que permite descrever a estrutura da API de forma clara e interativa.

## Como testar:
- Clone o repositório
- Abra com VS Code
- Crie um arquivo.env na raiz do projeto
```bash
DATABASE_URL="mysql://root@localhost:3306/pedidosapi?schema=public&timezone=UTC"
```
- Abra o termninal (Ctrl +')
- Execute os comandos
```bash
npm install
npx prisma init --datasource-provider mysql
npx prisma migrate dev --name init
npx nodemon
```
- Não esqueça de estar com o xampp mysql rodando
