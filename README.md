**GastoTrack 💸**
Projeto 1 da disciplina Programação Web Fullstack (ES47B / ES71) — UTFPR Campus Cornélio Procópio.
O objetivo foi desenvolver o frontend de uma aplicação web usando React.js + AJAX, seguindo o conceito de SPA (Single Page Application).

**Sobre o projeto**
A aplicação é um controle de gastos pessoais. Você consegue adicionar despesas com descrição, valor, categoria e data, visualizar um resumo dos seus gastos por categoria e ainda converter o total para outras moedas usando uma API externa de câmbio em tempo real.
Escolhi esse tema porque achei mais interessante do que usar uma API aleatória de coisas sem sentido, e também porque é algo que eu realmente usaria no dia a dia.

**📡 API externa utilizada**
ExchangeRate-API — https://api.exchangerate-api.com/v4/latest/BRL
Endpoint público e gratuito, sem necessidade de chave. Retorna as taxas de câmbio em relação ao BRL. O Summary.jsx faz a requisição via fetch toda vez que o total muda ou o usuário troca a moeda de destino.
Caso a requisição falhe (sem internet, por exemplo), a aplicação exibe uma mensagem de erro logo abaixo do seletor de moeda.

**Como Rodar o projeto localmente:**

# Clone o repositório
git clone https://github.com/seu-usuario/expense-tracker.git
cd expense-tracker

# Instale as dependências
npm install

# Rode em modo desenvolvimento
npm run dev
