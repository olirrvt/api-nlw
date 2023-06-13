# API de Hábitos

Este projeto é uma API desenvolvida em TypeScript que utiliza a ORM Prisma para gerenciar os dados de hábitos de um usuário. A API permite listar, criar, atualizar e excluir hábitos.

## Funcionalidades

- Listagem de hábitos: a API permite listar todos os hábitos de um usuário.
- Criação de hábitos: é possível criar um novo hábito associado a um usuário.
- Atualização de hábitos: permite atualizar as informações de um hábito existente.
- Exclusão de hábitos: é possível remover um hábito do sistema.
- Utilização da ORM Prisma: o projeto utiliza a ORM Prisma para interagir com o banco de dados.

## Requisitos

- Node.js
- Banco de dados PostgreSQL
- Prisma
- Visual Studio Code (ou outro editor de código compatível com TypeScript)

## Instalação

1. Faça o clone do repositório.
2. Abra o terminal e navegue até a pasta do projeto.
3. Execute o comando `npm install` para instalar as dependências.
4. Configure o arquivo `.env` com as informações do banco de dados.
5. Execute o comando `npx prisma migrate dev` para executar as migrações do banco de dados.
6. Execute o comando `npm run dev` para iniciar a API.

## Uso

1. Utilize uma ferramenta como o Postman ou Insomnia para fazer requisições à API.
2. Utilize o endpoint `/habits` para listar todos os hábitos de um usuário (GET).
3. Utilize o endpoint `/habits` para criar um novo hábito (POST).
4. Utilize o endpoint `/habits/:id` para atualizar um hábito existente (PUT).
5. Utilize o endpoint `/habits/:id` para excluir um hábito (DELETE).

## Contribuição

Contribuições são bem-vindas! Se você quiser melhorar esta API de hábitos, siga as etapas abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para a sua funcionalidade (`git checkout -b minha-funcionalidade`).
3. Implemente as melhorias ou correções necessárias.
4. Faça commit das suas alterações (`git commit -m 'Implementei a funcionalidade X'`).
5. Faça push para a branch criada no seu fork (`git push origin minha-funcionalidade`).
6. Abra um Pull Request no repositório original.

## Autor

Este projeto foi desenvolvido por Taylor Oliveira. Você pode entrar em contato comigo pelo taylorso2004@hotmail.com.
