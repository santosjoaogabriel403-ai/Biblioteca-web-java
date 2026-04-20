Sistema de Controle de Biblioteca

Projeto feito em Java usando Spring Boot, Thymeleaf e MongoDB (Atlas).
Serve para gerenciar livros, usuários, funcionários, reservas, multas e empréstimos.

Como rodar:
1. Ter Java 17 instalado
2. Ter Maven instalado
3. Configurar o arquivo application.properties com a URI do MongoDB Atlas
   Exemplo:
   spring.data.mongodb.uri=mongodb+srv://usuario:senha@cluster/biblioteca
   spring.data.mongodb.database=biblioteca
4. No terminal, dentro da pasta do projeto:
   mvn spring-boot:run
5. Abrir no navegador:
   http://localhost:8080/

Funcionalidades:
- Menu principal com links para todas as páginas
- CRUD de Livros
- CRUD de Usuários
- CRUD de Funcionários
- CRUD de Reservas
- CRUD de Multas
- CRUD de Empréstimos
- Todas as páginas têm botão para voltar ao menu

Estrutura:
- Model: classes das entidades
- Repository: interfaces para acessar o banco
- Service: regras de negócio
- Controller: rotas e lógica da aplicação
- Templates: páginas HTML com Thymeleaf
