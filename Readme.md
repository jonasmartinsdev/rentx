### Repositórios
e responsável por fazer inserção no banco de dados, fazer o select e manipulação de dados


### Testes unitários
e quando vamos testar uma parte da nossa aplicação
testamos a regra de negocio, testando a logica, como os casos de sucesso e erro,
"nao testamos o nosso banco de dados, nem api externa"

### Testes de integração
nos testamos o fluxo completo da nossa aplicação, desde as rotas, chamando os serviços do banco de dados fake, entre 

-> routes -> controllers -> useCases -> repository
<- repository <- useCases <- controllers <- routes


### TDD - Test Driven Development
E uma metodologia, onde primeiro criamos os nossos testes, depois criamos a aplicação