# curso-vue3

Este repositório contém o código-fonte do [Curso gratuito Vue.js 3](https://bit.ly/3QbEVRy) ministrado pelo [Tiago Matos](https://github.com/tiagomatosweb). O projeto desenvolvido durante o curso é uma aplicação de lista de tarefas (To-Do Task).

## Ferramentas Utilizadas

- Vue 3
- Tailwind CSS
- Axios
- Vue Router
- HTML
- CSS
- JavaScript

## Etapas do Desenvolvimento

1. Configuração do ambiente de desenvolvimento
2. Criação do projeto com Vue CLI
3. Configuração do Tailwind CSS
4. Estruturação dos componentes principais
5. Implementação do Vue Router
6. Gerenciamento de estado com Vuex
7. Integração com API usando Axios
8. Estilização e responsividade

## Como Rodar o Projeto

### Usando npm

1. Instale as dependências:
    ```bash
    npm install
    ```

2. Rode o servidor de desenvolvimento:
    ```bash
    npm run serve
    ```

### Usando yarn

1. Instale as dependências:
    ```bash
    yarn install
    ```

2. Rode o servidor de desenvolvimento:
    ```bash
    yarn serve
    ```

Agora você pode acessar o projeto no seu navegador através do endereço `http://localhost:8080`.

## Como Rodar o Backend

1. Instale o JSON Server globalmente (caso ainda não tenha):
    ```bash
    npm install -g json-server
    ```

2. Navegue até o diretório onde está o arquivo `database.json`.

3. Inicie o JSON Server:
    ```bash
    json-server --watch database.json
    ```

Agora você pode acessar o backend no endereço `http://localhost:3000`.