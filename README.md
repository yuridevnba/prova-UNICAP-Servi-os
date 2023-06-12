# springboot_aos
- API rodando na URL:  https://springbootservice-production.up.railway.app
- /funcionário (endpoint) {CRUD}
- /evento (endpoint) {CRUD}
- /gesor (endpoint)  {CRUD}
- Utilize uma ferramenta para testar a API com os metodos POST,PUT,DELETE E GET

## Exemplo de requisição POST

```bash
 {
      "idFuncionario": 1,
      "nome": "Yuri",
      "email": "yuri@example.com",
      "senha": "123456"
    }
```

```bash

{
  "data": "8/05/2022",
  "horarioInicio": "11h",
  "quantidade": "3",
  "horarioFinal": "12h",
  "local": "rua",
  "criadorDoEvento": "Eu",
  "email":"@email.com",
  "inscritos": [

   
		
		{
	"idFuncionario": 1,
	"nome": "Bi",
	"email": "Bi@example.com",
	"senha": "12345"
},
		{
	"idFuncionario": 2,
	"nome": "yuri",
	"email": "yuri@example.com",
	"senha": "12345"
}
	]
}

