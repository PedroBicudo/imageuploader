<div align="center">
    <h2>Image uploader</h2>
    <p>Aplicação Full stack de upload e acesso a imagens</p>
    <a href="https://imageuploader-pedrobicudo.herokuapp.com/swagger-ui.html">Documentação da API</a><br/>
    <a href="https://imageuploader-pedrobicudo.netlify.app/upload">Site</a>
</div>

## Motivação
Resolver o desafio [image uploader](https://devchallenges.io/challenges/O2iGT9yBd6xZBrOcVirx) do site [DevChallenges](https://devchallenges.io/).

### Projeto
<img src="https://user-images.githubusercontent.com/43938917/182935833-9c10992b-ca99-4a83-8864-4ba733be6549.gif" width="300"/>


## Como executar o projeto?
- Siga o passo a passo dos dois submódulos:
  - [Back end](https://github.com/PedroBicudo/imageuploadapi)
  - [Front end](https://github.com/PedroBicudo/imageuploadfrontend)

## Informações extras

### Problemas que eu tive

- Fazer o upload de arquivos usando o swagger
- Mostrar imagens como resposta no swagger

### O que eu aprendi

- Usar a classe [MultiPartFile](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/multipart/MultipartFile.html) para obter upload de arquivos.
- Aprendi que para fazer o upload de arquivos o content-type deve estar definido como multipart/form-data
- Aprendi a fazer o upload de arquivos no Postman e Swagger doc
- Aprendi a usar o swagger com OpenAPI
- Aprendi a gerar cabeçalho de maneira dinâmica.
- Aprendi a usar o Content-Dispoition no cabeçalho HTTP
- Eu descobri que eu estava usavando o status code Found errado, a função dele está ligada ao redirecionamento, enquanto o status code Ok está relacionado ao retorno de dados.
- Aprendi a usar o Scheduled para executar ações em intervalos, no projeto a cada uma hora todas as imagens cadastradas antes de um horário específico são apagadas.
- Aprendi a fazer o upload de imagens no Angular
- Aprendi a usar o a biblioteca dropzone do Angular
- Aprendi a usar submódulos no Git

### Tecnologias usadas
**Front end**
- HTML e CSS
- Typescript, Angular, NgrxDropzone, Clipboard
- Figma

**Back end**
- Java
- Spring, Spring Boot, Spring Data, Spring Web
- Postgres
- Flyway
- JUnit5
- Mockito
- Testcontainers

### Autor
- Linkedin - [PedroBicudo](https://www.linkedin.com/in/pedro-bicudo)

