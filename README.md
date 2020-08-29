# spring-aula

`Para acessar ao banco de dados em memoria, vocês vão utilizar a url localhost:8080/h2



Para acessar as requisições via postman, vocês devem baixar ele, porque via navegor ta dando problema.
Todas as requisições para paciente começam com localhost:8080/paciente
Pra fazer o post, vocês podem usar esse json aqui como teste de inserção na base:

{
        "nome":"Claudio",
        "cpf":"1234567",
        "dataNascimento": null,
        "endereco": null
    }

Para fazer o get, basta mudar o tipo de requisição no postman, ele deve trazer um resultado como esse aqui:
[
    
    {
        "id": 2,
        "nome": "Claudio",
        "dataNascimento": null,
        "sexo": null,
        "endereco": null,
        "cpf": "123456"
    }
]
