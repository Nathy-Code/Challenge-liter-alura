# Challenge Alura

Programa ONE(Oracle Next Education) && Alura - Especialização em back-end.
Este projeto foi desenvolvido como parte do Challenge da Alura, com o objetivo de criar um catálogo de livros utilizando a linguagem Java.

Funcionalidades
O programa permite a interação com o usuário por meio de um menu no console, oferecendo diversas opções para explorar o catálogo de livros.

Integração com a API Gutendex
Para construir o catálogo, o programa consome a API Gutendex, que fornece dados sobre livros e autores. As informações obtidas da API são desserializadas utilizando a biblioteca Jackson Databind, e em seguida armazenadas em um banco de dados PostgreSQL.

Tecnologias Utilizadas
Java: Linguagem de programação principal do projeto.

API Gutendex: Fonte de dados sobre livros e autores.

PostgreSQL: Banco de dados relacionais utilizado para armazenar as informações.

Jackson Databind: Biblioteca utilizada para desserializar os dados JSON da API em modelos de negócio.

Como Executar o Projeto
1- Clone este repositório para sua máquina local.

2- Configurar o banco de dados PostgreSQL.

3- Atualize o arquivo de configuração application.properties com as credenciais do seu banco de dados.

4- Execute o programa via console e navegue pelas opções do menu para explorar o catálogo de livros.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.
