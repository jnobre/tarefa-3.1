# Programação Web Avançada

## Tarefa 3.1 b)

Este repositório representa a proposta de solução para a tarefa 3.1 alinea b). Os Wireframes foram desenvolvidos na plataforma draw.io. 

De forma a compreender melhor as necessidades das duas novas entidades, testei a API com a ferramenta Postman, enviando um request do tipo POST com o body esperado pelo servidor, como é descrito na documentação das APIs do projecto. O user criado foi jnobre com a password 123.

#### Request:

```json
{
    "name": "João Nobre",
    "type": "admin",
    "birth_date": "1991-03-19",
    "description": "Test-uab",
    "location": {
        "city": "Coimbra",
        "district": "Coimbra",
        "country": "Portugal"
    },
    "auth": {
        "username": "jnobre",
        "password": "123"
    }
}
```

### Response: 

```json
{
    "http": 201,
    "code": "UserCreated",
    "type": "success",
    "body": {
        "gamification": {
            "points": 0,
            "quiz": null
        },
        "active": true,
        "_id": "6087ccc4a81e2a0004a55d41",
        "name": "João Nobre",
        "type": "admin",
        "birth_date": "1991-03-19T00:00:00.000Z",
        "description": "Testuab",
        "location": {
            "city": "Coimbra",
            "district": "Coimbra",
            "country": "Portugal"
        },
        "auth": {
            "username": "jnobre",
            "password": "$2a$04$LtvsBvwBr0.gByFxs0sY5Orz.mcSHkXq4cU7D4NG6fdgapht6fel.",
            "public_key": "6xvqqhcn0sl6087ccc4a81e2a0004a55d41",
            "private_key": "h0s9i383m5o6087ccc4a81e2a0004a55d41"
        },
        "registration_date": "2021-04-27T08:35:16.292Z",
        "__v": 0
    }
}
```

### Wireframes

Browser: [Viewer](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=Oepliag7sPoOdZmjJbbF#G1UtoM9lLudevaDxgiEKkVN0QICoP9f2sg)

Mobile: [Viewer](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1#G1zmbUmnDt-584DBIALFURkIHKLhgxERt_)

No directório Wireframe estão os ficheiros .png que representam os Wireframes.

### Mockups

No directório Mockups estão os ficheiros .png que representam os Mockups.

### Prototipo

No directório estão os Protótipos estão os ficheiros html que representam os wireframes e os mockups criados em HTML5. 

### Referências

* [Documentação da API](https://documenter.getpostman.com/view/4604741/SWE6byDX#3a10ba2a-c739-4122-9484-f3a277bf41b3)
* [Back-office do animalec](https://fcawebbook2.herokuapp.com/)
* [Animalec](https://rqueiros.github.io/vue-animalec/)
* Livro "Desenvolvimento avançado para a web". Ricardo Queirós & Filipe Portela 
