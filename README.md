## Almoxarifado API - Gerenciando seu Estoque

Este projeto tem como objetivo criar uma API RESTful simples para gerenciar o estoque de um almoxarifado, utilizando Spring Boot como framework principal. A API permitirá realizar operações básicas de CRUD (Create, Read, Update, Delete) para produtos, proporcionando uma interface prática para controle do estoque.

### Objetivo

O objetivo principal é fornecer uma solução eficiente e organizada para gerenciar o estoque de um almoxarifado, utilizando tecnologias modernas e boas práticas de desenvolvimento.

### Recursos da API

* **CRUD de Produtos:**
    * **Criar:** Adicionar novos produtos ao estoque.
    * **Ler:** Listar todos os produtos cadastrados.
    * **Atualizar:** Alterar informações de produtos existentes, como quantidade ou preço.
    * **Deletar:** Remover produtos específicos do estoque.
* **Tratamento de Erros:** Implementar mecanismos para lidar com erros e fornecer respostas informativas ao usuário.

### Tecnologias Utilizadas

* **Spring Boot:** Framework Java para desenvolvimento rápido de aplicações web.
* **Spring Data JPA:** Simplifica a interação com bancos de dados, facilitando a persistência de dados.
* **MySQL:** Sistema de gerenciamento de banco de dados relacional (RDBMS) utilizado para armazenar os dados do estoque.
* **Postman:** Ferramenta para testar os endpoints da API e verificar seu funcionamento.

### Arquitetura

O projeto segue uma estrutura organizada em camadas:

* **Camada de Controladores:** Responsável por receber as requisições HTTP e delegar o processamento para as camadas de serviço e repositório.
* **Camada de Serviços:** Contém a lógica de negócio da aplicação, realizando operações como validações e regras de negócio.
* **Camada de Repositórios:** Interage com o banco de dados, realizando operações de persistência de dados.

### Como Usar

1. **Clone o repositório:** Faça o download do código-fonte do projeto.
2. **Configure o banco de dados:** Crie um banco de dados MySQL e configure as credenciais de acesso no arquivo de configuração da aplicação.
3. **Execute a aplicação:** Inicie a aplicação Spring Boot.
4. **Utilize o Postman:** Utilize o Postman para testar os endpoints da API e verificar o funcionamento das operações CRUD.


### Contato

Para qualquer dúvida ou sugestão, entre em contato pelo sarmanhof9@gmail.com ou visite meu perfil no LinkedIn: https://www.linkedin.com/in/felipe-carneiro-de-albuquerque-sarmanho-9521b0306/

