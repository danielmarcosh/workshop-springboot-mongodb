# Projeto MongoDB com Spring Boot
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/LICENSE) 

# Sobre o projeto

https://course-javasb-danmarche.herokuapp.com/users

O projeto é uma api restfull com **Spring Boot e com o banco MongoDB**. Este projeto foi desenvolvido durante o **Curso: Java COMPLETO - Programação Orientada a Objetos + Projetos** do [Prof. Dr. Nelio Alves](http://educandoweb.com.br "Site do Prof. Dr. Nelio Alves").
A aplicação consiste em um **Sistema  de 'posts' e comentários**, onde um usuário faz um post e este post pode receber comentários de outros usuários. No sitema temos as Entidades Usuário, Post e Comentário.
O projeto está estruturado em camadas lógicas: **Controladores Rest**, **Camadas de Serviço** e a **Camada de acesso a Dados**. Foi desenvolvido as operações de **CRUD** das Entidades, utilizamos o Banco de Dados **MongoDB**.

## Listando todos os usuários
![img1](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/ListarUsuarios.jpg)

## Buscando um usuário por ID
![img 2](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/BuscaID.jpg)

## ID não encontrado
![img 3](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/BuscaIDErro.jpg)

## Criar novo usuário
![img 4](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/CriarUsuario.jpg)

## Editando dados de um usuario
![img 5](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/EditarUsuario.jpg)

## Erro ao editar ID inválido
![img 6](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/EditarUsuarioErro.jpg)

## Deletando um usuário
![img 7](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/DeletarUsuario.jpg)

## Erro ao deletar usuário com ID inválido
![img 8](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/DeletarUsuarioErro.jpg)

## Modelo conceitual
![img 9](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/dominio.jpg)

## Estrutura do Projeto
![img 10](https://github.com/danielmarcosh/workshop-springboot-mongodb/blob/master/assets/Estrutura.jpg)

# Tecnologias utilizadas
## Backend
- Java
- SpringBoot
- Spring Data
- MongoRepository
- Maven
- PostMan
## Banco de Dados
- MongoDB


# Como executar o projeto

## Aplicação
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/danielmarcosh/workshop-springboot-mongodb.git
```
```java
// Abrir o projeto 'workshop-springboot-mongodb' no editor Eclipse ou em um de editor de sua preferencia
// Para rodar o projeto. Vai no diretório 'workshop-springboot-mongodb/src/main/java/com/danmarche/workshopmongo/'
// E execute o arquivo 'WorkshopmongoApplication.java'
WorkshopmongoApplication.java
```

### Agradecimentos
Os meus sinceros agradecimentos ao [Prof. Dr. Nelio Alves](http://educandoweb.com.br "Site do Prof. Dr. Nelio Alves"), por este excelente curso, no qual eu pude aprender muito e a praticar todos os conhecimentos durante o curso, desejo ao professor muito sucesso em sua carreira!

# Autor

Daniel Marcos Hermenegildo
danielmarcosh@gmail.com / danielmh321@hotmail.com

https://www.linkedin.com/in/daniel-marcos-24260a132
