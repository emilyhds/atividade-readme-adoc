# 📚 Sistema de Gerenciamento de Biblioteca

## 🎯 Sobre o Projeto
O Sistema de Gerenciamento de Biblioteca foi desenvolvido para facilitar o
processo de empréstimo, devolução e gerenciamento de livros em uma
biblioteca. Através da aplicação, é possível gerenciar empréstimos de livros,
disponibilidade de exemplares, cadastro de usuários e gerar relatórios de
atividades. O sistema visa melhorar a experiência do usuário e otimizar a
administração da biblioteca, garantindo uma gestão eficiente e eficaz.

## 🚀 Recursos

* 📕 **Cadastro e gerenciamento de livros** com informações detalhadas (título, autor, ISBN, etc.).
* 🖊️ **Criação e modificação de empréstimos** de livros, com opções de data de empréstimo e devolução.
* 👁️ **Visualização da disponibilidade dos livros** em tempo real.
* 📁 **Geração de relatórios** de empréstimos, devoluções e multas.
* 🔔 **Notificação de usuários** sobre empréstimos e devoluções.
* 👥 **Sistema de login e autenticação** para administradores e usuários.
  
## 🖥️ Tecnologias Utilizadas

1. **Frontend**
   * **Angular**: Framework utilizado para o desenvolvimento da interface de usuário,
      permitindo uma aplicação interativa e responsiva.
2. **Backend**
   * **Spring Boot (Java)**: Framework utilizado para o desenvolvimento da API, que gerencia os empréstimos,
     os livros e os usuários.
3. **Banco de Dados**
   * **MySQL**: Banco de dados relacional utilizado para armazenar informações sobre empréstimos,
     usuários e livros.
4. **Autenticação**
   * **JWT (JSON Web Tokens)**: Utilizado para garantir a segurança no processo de autenticação e autorização de usuários.

## 🎮 Como Executar

1. **Clone o repositório**: <br>
   Clone o repositório para o seu ambiente local com o comando:
   
```sh
git clone https://github.com/seu-usuario/taskflow.git
```

2. **Instale as Dependências do Frontend**: <br>
  Navegue até o diretório do frontend e instale as dependências com npm:

```sh
cd sistema-biblioteca/frontend
npm install
```

3. **Instale as Dependências do Backend**: <br>
  Navegue até o diretório do backend e instale as dependências com Maven:

```sh
cd sistema-biblioteca/backend
mvn install
```

4. **Configuração do Banco de Dados**: <br>
  Crie um banco de dados MySQL e configure as credenciais no
arquivo application.properties do backend. Em seguida, execute as
migrações para criar as tabelas necessárias:

```sh
spring.datasource.url=jdbc:mysql://localhost:3306/biblioteca
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

5. **Inicie o Servidor Backend**: <br>
  Inicie o servidor do backend com o comando:

```sh
mvn spring-boot:run
```

6. **Inicie o Servidor Frontend**: <br>
 Inicie o servidor do frontend com o comando:

```sh
ng serve
```

7. **Acesse a Aplicação**: <br>
 Abra o navegador e acesse a aplicação na URL: http://localhost:4200.

Após executar esses comandos, o servidor estará rodando e você poderá acessar a aplicação no endereço `http://localhost:8080`.

## 📃 Documentação da API
A API do Sistema de Gerenciamento de Biblioteca foi documentada
utilizando Swagger, permitindo uma visualização interativa e detalhada de
todos os endpoints disponíveis. Abaixo estão alguns dos endpoints principais:

* **GET /api/books:** Retorna todos os livros disponíveis.
* **POST /api/loans:** Cria um novo empréstimo de livro.
* **GET /api/loans/{id}:** Obtém os detalhes de um empréstimo específico.
* **PUT /api/loans/{id}:** Atualiza informações de um empréstimo.
* **DELETE /api/loans/{id}:** Cancela um empréstimo.

Para acessar a documentação completa da API no Swagger, inicie o servidor
backend e acesse:

```sh
http://localhost:8080/swagger-ui.html
```

## 🤝 Contribuindo
Contribuições são bem-vindas! Se você deseja contribuir para o projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma nova branch `git checkout -b feature-nome-da-feature`.
3. Faça as alterações e commit `git commit -am &#39;Adiciona nova feature`.
4. Envie para o repositório original `git push origin feature-nome-da-feature`.
5. Abra um Pull Request descrevendo as mudanças feitas.

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para
mais detalhes.

## ✉️ Contato
Se você tiver alguma dúvida ou sugestão, entre em contato com a equipe de
desenvolvimento:

* **Email**: contato@biblioteca.com
* **Telefone**: +55 11 98765-4321
