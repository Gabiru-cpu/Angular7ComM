# Projeto de Live Tracker

Este é um projeto que consiste em um backend desenvolvido em Java usando o framework Spring e o banco de dados MongoDB para registrar informações sobre lives realizadas. O frontend é construído usando o Angular, permitindo que as lives já realizadas e agendadas sejam exibidas. Além disso, o frontend possui um botão para adicionar novas lives através da interface.

## Funcionalidades

- Registro de lives: O backend é responsável por receber as informações sobre as lives, como título, descrição, data e hora de início, e armazená-las no banco de dados MongoDB.
- Listagem de lives: O frontend consome os dados do backend e exibe as lives já realizadas e agendadas em uma interface amigável.
- Adição de novas lives: O frontend possui um formulário para inserir as informações de uma nova live e enviá-las ao backend para registro no banco de dados.

## Tecnologias utilizadas

- Backend:
  - Java: Linguagem de programação principal para o desenvolvimento do backend.
  - Spring Framework: Framework utilizado para criar a estrutura do aplicativo web.
  - MongoDB: Banco de dados NoSQL utilizado para armazenar as informações sobre as lives.

- Frontend:
  - Angular: Framework JavaScript utilizado para construir a interface do usuário interativa.
  - HTML/CSS: Linguagens de marcação e estilização utilizadas para criar a estrutura e o visual do frontend.
  - TypeScript: Linguagem de programação usada para desenvolver a lógica do frontend.

## Configuração do projeto

Siga as etapas abaixo para configurar e executar o projeto em seu ambiente local:

### Pré-requisitos

- Java Development Kit (JDK) 8 ou superior instalado.
- Node.js e npm (Node Package Manager) instalados.

### Backend

1. Clone o repositório do projeto para o seu ambiente local.
2. Navegue até o diretório do backend.
3. Abra o arquivo `application.properties` e configure as informações de conexão com o banco de dados MongoDB, se necessário.
4. Execute o comando `./mvnw spring-boot:run` para iniciar o servidor backend.

### Frontend

1. Navegue até o diretório do frontend.
2. Execute o comando `npm install` para instalar as dependências do projeto.
3. Após a conclusão da instalação, execute o comando `npm start` para iniciar o servidor de desenvolvimento do Angular.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests para melhorar este projeto.
