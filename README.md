# Desafio de Programação Java Jr.

# O que preciso fazer?

Vamos ser práticos e diretos, se você quer trabalhar conosco siga os passos abaixo:

* Faça um "fork" desse projeto para sua conta GitHub.
* Implemente o desafio descrito no tópico abaixo.
* Faça um push para seu repositório com o desafio implementado.
* Envie um email para (alexandrecampos@compayz.com) com cópia para (alexandreferreira@compayz.com) avisando que finalizou o desafio com a url do seu fork.

# Desafio de Clientes, Produtos e Pedidos

Você deverá criar uma aplicação para cadastramento de clientes, produtos e pedidos:

**Back-end:** aplicação JavaEE baseada em Web Services no padrão RESTful JAX-RS.

**Requisitos:**

- Permitir o cadastro de clientes
- Permitir o cadastro de produtos
- Permitir o registro de pedidos para clientes

O cadastro do cliente deve conter as seguintes informações:

* Código
* Nome
* CPF
* Telefone
* E-mail

O cadastro de produto deve contar as seguintes informações:

* Código
* Descrição
* Unidade
* Valor

Os Pedidos contém as seguintes informações:

* Numero da Pedido
* Data de emissão
* Descrição (Apenas texto)
* Lista de Produtos
* Valor Total(Deverá ser calculado através da soma do valor de todos os produtos vinculados ao pedido)

### Tecnologias

Escolha umas das opções abaixo para implementar sua solução. A modelagem dos dados fica a seu critério. Não se preocupe com autenticação.

#### BACK-END

**Opção 1**

* Aplicação JavaEE utilizando framework Quarkus
* Banco de dados PostgreSQL
* RESTFul API ou Jersey JAX-RS

**Opção 2**

* Aplicação pura Java EE (não utilize Spring, Struts, EJB, etc)
* RESTful API JAX-RS utilizando Servlets ou framework Jersey
* Banco de dados SQL (MySQL, PostgreSQL, HSQLDB) com JPA

**Recomendações gerais:**

* Não utilize frameworks ou BD que não foram indicados
* Para servidor de aplicação utilize Jetty ou Tomcat (Não utilize: JBOSS, Wildfly ou qualquer outro servidor. Por quê? Critério de facilidade de configuração)
* Utilize o Maven para gerenciamento de dependências


### Arquitetura e documentação

No arquivo README do projeto explique o funcionamento e a arquitetura da solução adotada na sua implementação. Descreva também os passos para executar corretamente seu projeto.

### Avaliação

Entre os critérios de avaliação estão:

* Facilidade de configuração do projeto
* Performance
* Código limpo e organização
* Documentação de código
* Documentação do projeto (readme)
* Arquitetura
* Boas práticas de desenvolvimento
* Design Patterns

### DICA

* Utilize testes automatizados para inserir os dados
* Utilize alguma ferramenta(eq. Postman) para realizar as chamadas via get/post para inserir e exibir os dados
