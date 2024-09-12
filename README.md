# Desafio BackEnd Fusion: Criar e Gerenciar a Galáxia Inspirada em Star Wars

## Objetivo

Desenvolver uma API backend que permita a criação, gerenciamento e visualização de uma galáxia inspirada em Star Wars, incluindo planetas, sistemas estelares, personagens e naves espaciais. A API deve ser robusta, segura e eficiente, demonstrando habilidades em desenvolvimento backend.

## Requisitos do Projeto

### Estrutura da API

- A API deve ser desenvolvida usando Node.js com NestJS ou Express. 🚀
- Utilizar TypeScript para tipagem estática.
- A API deve seguir os princípios RESTful. 🌐

### Entidades

- **Planetas**: Nome, clima, terreno, população. 🌍
- **Sistemas Estelares**: Nome, descrição, lista de planetas. ✨
- **Personagens**: Nome, raça, afiliação (Jedi, Sith, Rebelde, etc.), planeta natal. 🦸
- **Naves Espaciais**: Nome, modelo, fabricante, capacidade de passageiros. 🚀

### EndPoints

#### Planets

- `POST 📤 /planets`: Criar um novo planeta.
- `GET 📥 /planets`: Listar todos os planetas.
- `GET 📥 /planets/:id`: Obter detalhes de um planeta específico.
- `PUT 🔄 /planets/:id`: Atualizar informações de um planeta.
- `DELETE 🗑 /planets/:id`: Deletar um planeta.

#### Star Systems

- `POST 📤 /star-systems`: Criar um novo sistema estelar.
- `GET 📥 /star-systems`: Listar todos os sistemas estelares.
- `GET 📥 /star-systems/:id`: Obter detalhes de um sistema estelar específico.
- `PUT 🔄 /star-systems/:id`: Atualizar informações de um sistema estelar.
- `DELETE 🗑 /star-systems/:id`: Deletar um sistema estelar.

#### Characters

- `POST 📤 /characters`: Criar um novo personagem.
- `GET 📥 /characters`: Listar todos os personagens.
- `GET 📥 /characters/:id`: Obter detalhes de um personagem específico.
- `PUT 🔄 /characters/:id`: Atualizar informações de um personagem.
- `DELETE 🗑 /characters/:id`: Deletar um personagem.

#### SpaceShips

- `POST 📤 /spaceships`: Criar uma nova nave espacial.
- `GET 📥 /spaceships`: Listar todas as naves espaciais.
- `GET 📥 /spaceships/:id`: Obter detalhes de uma nave espacial específica.
- `PUT 🔄 /spaceships/:id`: Atualizar informações de uma nave espacial.
- `DELETE 🗑 /spaceships/:id`: Deletar uma nave espacial.

### Autenticação e Autorização

- Implementar autenticação de usuários usando JWT. 🔒
- Os usuários devem ser categorizados com base em afiliações como Jedi, Sith, Rebeldes, etc. 🛡️
- Proteger os endpoints para que apenas usuários autenticados possam criar, atualizar e deletar dados. 🛡️

### Banco de Dados

- Usar qualquer banco de dados, relacional ou não-relacional. 🗃️
- Utilizar qualquer ORM de sua escolha. 🔄

### Validação e Tratamento de Erros

- Implementar validação de dados de entrada. ✅
- Gerenciar e retornar mensagens de erro apropriadas. 🚫

### Documentação da API (Opcional)

- Documentar a API usando Swagger ou Postman (não obrigatória). 📜
- Incluir exemplos de requisições e respostas (schemas). 📝

### Testes (Opcional)

- Escrever testes unitários e de integração para a API usando Jest (não obrigatória). 🧪

## Tecnologias e Ferramentas

- **Linguagens**: TypeScript
- **Frameworks**: NestJS ou Express

## Extras

- **Deploy**: Hospedar a API em um serviço como Heroku, AWS, ou DigitalOcean. 🌐
- **Logs e Monitoramento**: Implementar logs e monitoramento para a API usando ferramentas como Winston ou Morgan. 📊

## Submissão

- **Repositório GitHub**: Submeter o código em um repositório público no GitHub. 📂
- **Documentação**: Incluir um `README.md` detalhado com instruções de instalação, uso e qualquer informação relevante. 📝
- **Demo**: Fornecer um link para a API hospedada e a documentação. 🌐
- **Prazo**: O prazo para submissão é de 15 dias a partir da data de início. ⏳

## Como Participar

1. Faça um fork deste repositório. 🍴
2. Crie um branch com seu nome: `nome-sobrenome`.
3. Após completar o desafio, envie o link do deploy, o repositório do código-fonte e o link da postagem no LinkedIn por e-mail para `projetofrontendfusion@gmail.com` com o assunto: "Entrega + Desafios[03] + Seu Nome". 📧

### Exemplo de E-mail

**Assunto:** Entrega + Desafio backend + João Silva

Olá,

Segue abaixo a entrega do Desafio backend para o processo seletivo do Frontend Fusion.

Nome: João Silva  
Link do GitHub: [https://github.com/joaosilva](https://github.com/joaosilva)  
Link do LinkedIn: [https://linkedin.com/in/joaosilva](https://linkedin.com/in/joaosilva)  
Data de Início: 01/09/2024  
Data de Entrega: 20/09/2024  
Link do GitHub com o Código: [https://github.com/joaosilva/desafio03](https://github.com/joaosilva/desafio03)  
Link do Deploy: [https://joaosilva.netlify.app](https://joaosilva.netlify.app)  
Link da Postagem no LinkedIn: [https://linkedin.com/posts/joaosilva/desafio-03](https://linkedin.com/posts/joaosilva/desafio-03)  

Agradeço a oportunidade e estou à disposição para qualquer dúvida.

Atenciosamente,  
João Silva

Boa sorte e estamos ansiosos para ver seu trabalho! 🚀

Este desafio faz parte do processo seletivo do projeto Frontend Fusion para a vaga de Desenvolvedor React Júnior.
