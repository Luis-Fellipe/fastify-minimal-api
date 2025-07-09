# Formula 1 - API Fastify + TypeScript

Este projeto é uma API desenvolvida em Node.js com TypeScript, utilizando o framework Fastify para criação de servidores web de alta performance. O objetivo é fornecer uma base simples, moderna e eficiente para desenvolvimento de APIs.

## 🚀 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://fastify.io/)
- [@fastify/cors](https://www.npmjs.com/package/@fastify/cors)
- [TSX](https://www.npmjs.com/package/tsx)
- [Tsup](https://www.npmjs.com/package/tsup)

## ⚙️ Configuração do Projeto

Para executar o projeto localmente, siga os passos abaixo:

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd fastify-minimal-api

# 2. Instale as dependências
npm install

# 3. Crie um arquivo .env com a variável de porta
echo "PORT=3333" > .env

# 4. Inicie o servidor em modo desenvolvimento
npm run start:dev
```

A API estará disponível em: http://localhost:3333

## 📦 Scripts disponíveis

- `npm run start:dev` – Inicia a aplicação em modo desenvolvimento com suporte ao `.env`
- `npm run start:watch` – Inicia com recarregamento automático em tempo real
- `npm run dist` – Compila o projeto TypeScript para JavaScript na pasta `/dist`
- `npm run start:dist` – Executa a versão compilada

## 🛡️ Licença

Este projeto está licenciado sob a licença ISC.
