# 🎮 DSList - Catálogo de Jogos

Projeto acadêmico desenvolvido em **Java 17 + Spring Boot**, utilizando **JPA, Hibernate, PostgreSQL** e **Maven**.  

Este projeto foi realizado durante o **Intensivão Java Spring** ministrado pelo professor **Nélio Alves**, sendo minha primeira introdução prática ao ecossistema Spring. 

---

## 🚀 Deploy
O deploy foi realizado no **Railway**, mas ficará disponível apenas temporariamente (teste gratuito de 1 mês).  
O foco deste repositório é a execução **local** do projeto.

---

## 🛠️ Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/Miguelmrg/dslist.git
   cd dslist
Configure o banco PostgreSQL:

Crie um banco chamado dslist

Ajuste application.properties com usuário e senha do seu PostgreSQL local

Rode o projeto com Maven:
   ```bash
   ./mvnw spring-boot:run
   ```
Acesse no navegador/cliente REST:

http://localhost:8080

📌 Endpoints disponíveis

GET /games → Lista todos os jogos

GET /games/{id} → Retorna jogo por ID (1 a 10)

GET /lists → Lista todas as listas

GET /lists/{id} → Retorna lista por ID (1 ou 2)

📸 Exemplos de Requisições

🔹 Listando todos os jogos (GET /games)


🔹 Buscando um jogo por ID (GET /games/1)


🔹 Listando todas as listas (GET /lists)


🔹 Buscando lista por ID (GET /lists/1)


✨ Créditos

Autor: Miguel Grillo

Projeto feito em acompanhamento com o Intensivão Java Spring do professor Nélio Alves
