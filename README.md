# Rocket Notes — Frontend

Interface web para criação e gerenciamento de notas com tags e links úteis.

![Preview](./preview.png)

## Sobre o projeto

Rocket Notes é uma aplicação fullstack desenvolvida durante a trilha Explorer da Rocketseat. O frontend consome a API REST do BackEnd-Notes e permite ao usuário criar, visualizar e excluir notas, organizar por tags e gerenciar o perfil.

## Funcionalidades

- Autenticação com login e criação de conta
- Criação de notas com título, descrição, tags e links
- Listagem e busca de notas por tag
- Visualização detalhada de cada nota
- Edição de perfil com upload de avatar

## Tecnologias

- React 18
- Vite
- React Router DOM
- Styled Components
- Axios

## Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/lukarodrigue/FrontEnd-Notes

# Instale as dependências
npm install

# Configure a URL da API no arquivo src/services/api.js
# Aponte para o backend rodando localmente (padrão: http://localhost:3333)

# Inicie a aplicação
npm run dev
```

Acesse em `http://localhost:5173`

> O backend precisa estar rodando. Veja o repositório [BackEnd-Notes](https://github.com/lukarodrigue/BackEnd-Notes).

## Autor

Luka Rodrigues Gonçalves · [LinkedIn](https://linkedin.com/in/lukarodrigue)
