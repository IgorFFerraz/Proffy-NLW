# Proffy - Plataforma de conexão entre alunos e professores

Um projeto Full-Stack desenvolvido para conectar professores e alunos. A plataforma permite que professores cadastrem suas aulas, definam preços e horários disponíveis, enquanto os alunos podem buscar por essas aulas e entrar em contato.

## Objetivo
O objetivo principal da aplicação é facilitar o encontro entre estudantes que precisam de ajuda em matérias específicas e professores disponíveis para ensinar, gerenciando disponibilidade de horários e filtragem por disciplinas. Além disso, tive como objetivo testar meus conhecimentos nas tecnologias utilizadas no projeto, treinando a aplicação e implementação correta das mesmas.

## Tecnologias Utilizadas

Esse projeto foi desenvolvido com as seguintes tecnologias:

**Frontend (Interface):**
- HTML5 & CSS3
- JavaScript (Vanilla)
- Nunjucks (Template Engine para renderização dinâmica)

**Backend (Servidor & Banco de Dados):**
- Node.js
- Express (Gerenciamento de rotas e requisições HTTP)
- SQLite (Banco de dados relacional)
- sqlite-async (Para lidar com operações assíncronas no banco)

## Funcionalidades
- **Cadastro de Professores:** Inserção de dados pessoais, matéria lecionada, custo por hora e grade de horários disponíveis.
- **Busca Dinâmica:** Alunos podem filtrar aulas por matéria, dia da semana e horário.
- **Banco de Dados Relacional:** Estruturação de dados conectando o perfil do professor, a matéria e a agenda.
- **Formulários Dinâmicos:** Adição de múltiplos horários de aula no frontend via JavaScript antes do envio para o servidor.

## Como executar o projeto

Caso queira rodar o projeto localmente na sua máquina, siga os passos abaixo:

1. Clone este repositório:
   `git clone https://github.com/IgorFFerraz/Proffy-NLW.git`

2. Instale as dependências:
   `npm install`

3. Inicie o banco de dados e o servidor:
   `npm run dev`

4. Acesse no seu navegador:
   `http://localhost:5500`
