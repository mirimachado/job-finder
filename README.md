# job-finder

Job Finder é uma aplicação Node.js para cadastro e busca de vagas de emprego, usando Express, Sequelize e Handlebars.

## Funcionalidades

- Cadastro de vagas de emprego
- Busca de vagas por palavra-chave
- Listagem das vagas mais recentes

## Tecnologias

- Node.js
- Express
- Sequelize (ORM)
- MySQL ou MariaDB
- Handlebars (template engine)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/job-finder.git
   cd job-finder
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure o banco de dados em `/db/connection.js` com seus dados de acesso.

4. Rode as migrations ou crie manualmente a tabela `Jobs` conforme o modelo.

## Como rodar

```bash
npm start
```
ou, para desenvolvimento com recarregamento automático:
```bash
npx nodemon app.js
```

## Acessando no navegador

Abra seu navegador e acesse:

[http://localhost:3000](http://localhost:3000)

---

