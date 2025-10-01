# ClassHub - Front-end 🎓

![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)

Repositório dedicado ao desenvolvimento do **Front-end (MVP)** da plataforma ClassHub, o projeto integrador do curso de Análise e Desenvolvimento de Sistemas.

## 📖 Sobre o Projeto

> O ClassHub é uma plataforma marketplace que conecta professores e alunos de forma simples e eficiente. O objetivo é facilitar o acesso ao ensino personalizado, permitindo que alunos encontrem professores de acordo com a disciplina desejada, enquanto professores podem divulgar suas habilidades e disponibilizar horários para lecionar.

Esta é a implementação do **Produto Mínimo Viável (MVP)**, focada em validar as funcionalidades essenciais do negócio, oferecendo uma experiência de usuário limpa, intuitiva e responsiva.

---

## ✨ Funcionalidades do MVP

Este repositório implementa a interface de usuário para as seguintes funcionalidades:

* **👤 Gestão de Usuários e Autenticação**
    * [x] Tela de cadastro para Alunos e Professores.
    * [x] Tela de login seguro.
    * [x] Painel de usuário para visualização e edição de perfil (dados pessoais, foto, biografia, etc.).
    * [x] Interface para professores gerenciarem disciplinas, valor da hora-aula e horários.

* **📅 Interação e Agendamento de Aulas**
    * [x] Página de busca de professores com filtros (disciplina, valor, etc.).
    * [x] Visualização do perfil público dos professores com suas agendas.
    * [x] Modal ou página para solicitação de agendamento de aula.
    * [x] Painel para alunos e professores visualizarem aulas futuras e passadas.
    * [x] Opções na interface para confirmar, recusar ou cancelar agendamentos.

* **💳 Interface de Pagamentos**
    * [x] Tela para que o aluno realize o pagamento online no momento do agendamento (integração com gateway).

* **⭐ Avaliação e Reputação**
    * [x] Interface para o aluno avaliar um professor após a conclusão da aula.
    * [x] Exibição da nota média de avaliação no perfil do professor.

---

## 💻 Tecnologias Utilizadas

O front-end do ClassHub está sendo construído com as mais modernas tecnologias do mercado para garantir uma aplicação robusta, escalável e de fácil manutenção.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

Para o design e prototipação das interfaces, utilizamos o Figma.

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 🚀 Como Executar o Projeto

Para rodar o projeto localmente, siga os passos abaixo. Você vai precisar do [Node.js](https://nodejs.org/en/) e do [Git](https://git-scm.com/) instalados em sua máquina.

```bash
# 1. Clone este repositório
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)

# 2. Acesse a pasta do projeto
cd NOME-DO-REPOSITORIO

# 3. Instale as dependências
npm install
# ou
yarn install

# 4. Crie um arquivo .env na raiz do projeto
# Baseado no arquivo .env.example, adicione as variáveis de ambiente necessárias,
# como a URL da API do back-end.
# Exemplo:
# VITE_API_URL=http://localhost:3333

# 5. Rode a aplicação em modo de desenvolvimento
npm run dev
# ou
yarn dev

# O servidor de desenvolvimento iniciará em http://localhost:5173 (ou outra porta disponível)

👥 # Equipe de Desenvolvimento
<img src="[https://raw.githubusercontent.com/SEU-USUARIO/SEU-REPO/main/assets/images/tiago.jpg](https://github.com/T1P3R31R4/ClassHub---Front-end/blob/main/src/assets/imagens/tiago_profile.png?raw=true)" width="70px" alt="Foto de Tiago Jesus Pereira"/> Tiago Jesus Pereira......................Desenvolvedor Front-end (PO) - Link para o GitHub
(Foto) Felipe Piske Teles.......................Desenvolvedor Backand   - Link para o GitHub
(Foto) Lucas Fernandes..........................Desenvolvedor Backand   - Link para o GitHub
(Foto) Gustavo Kirst............................Desenvolvedor Front-end - Link para o GitHub
(Foto) Matheus Röhrig...........................Desenvolvedor Front-end - Link para o GitHub
