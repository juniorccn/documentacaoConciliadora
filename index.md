# Conecta

![](https://www.zazvendas.com.br/wp-content/uploads/2022/05/Logotipo-ZAZ-Vendas.png)

# Heading 1
## Heading 2               
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
# Heading 1 link [Heading link](https://github.com/pandao/editor.md "Heading link")
## Heading 2 link [Heading link](https://github.com/pandao/editor.md "Heading link")
### Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")
#### Heading 4 link [Heading link](https://github.com/pandao/editor.md "Heading link") Heading link [Heading link](https://github.com/pandao/editor.md "Heading link")
##### Heading 5 link [Heading link](https://github.com/pandao/editor.md "Heading link")
###### Heading 6 link [Heading link](https://github.com/pandao/editor.md "Heading link")

### Introdução

Essa API possibilita o registro de grupos e mantém seu registro para receber arquivos EDI (Electronic Data Interchange).

### Descrição do Produto

O Extrato Eletrônico é um produto disponibilizado pela Cielo aos clientes que necessitam de automatização no processo de conciliação. Nele, as informações são transmitidas de forma padronizada sem intervenção manual por meio do canal SFG (Sterling File Gateway), proporcionando agilidade e segurança no tráfego das informações. Ao lado, macrofluxo do serviço.

### Benefícios

- Permite a realização da conciliação contábil e financeira de forma automatizada
- Maior agilidade e eficiência operacional
- Integração com a automação comercial de vendas
- Segurança no recebiento das informações
- Atendimento Especializado

### Consulta conciliadora

O Extrato Eletrônico é um produto disponibilizado pela Cielo aos clientes que necessitam de automatização no processo de conciliação. Nele, as informações são transmitidas de forma padronizada sem intervenção manual por meio do canal SFG (Sterling File Gateway), proporcionando agilidade e segurança no tráfego das informações. Ao lado, macrofluxo do serviço.

1. O parceiro redireciona o cliente para {cielo-login-url}.
2. O cliente entra com suas credenciais e clica em Entrar.
3. A Cielo mostra os termos de autorização e o cliente aprova este acesso clicando em Permitir Acesso.
4.  A Cielo redireciona o cliente para o parceiro novamente em {partner-call-back-url}. 

### Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")


#### Request


> **POST** {cielo-api-base-url}/consent/v1/oauth/access-token POST {cielo-api-base-url}/consent/v1/oauth/access-token
> | Function name | Description                    |
> | ------------- | ------------------------------ |
> | `help()`      | Display the help window.       |
> | `destroy()`   | **Destroy your computer!**     |

```javascript
{
  products(first: 5, channel: "default-channel") {
    edges {
      node {
        id
        name
        description
      }
    }
  }
}
```

#### Response

```javascript
{
  "data": {
    "products": {
      "edges": [
        {
          "node": {
            "id": "UHJvZHVjdDoxMzY=",
            "name": "ABBA / Arrival",
            "description": "{\"time\": 1654858249725, \"blocks\": [{\"id\": \"0\", \"data\": {\"text\": \"\"}, \"type\": \"paragraph\"}], \"version\": \"2.23.1\"}"
          }
        },
        {
          "node": {
            "id": "UHJvZHVjdDoxMzQ=",
            "name": "Aniversario Los 10 Años De ABBA",
            "description": "{\"time\": 1654858217036, \"blocks\": [{\"id\": \"0\", \"data\": {\"text\": \"\"}, \"type\": \"paragraph\"}], \"version\": \"2.23.1\"}"
          }
        },
        {
          "node": {
            "id": "UHJvZHVjdDoxMzA=",
            "name": "Antologia",
            "description": "{\"time\": 1654858150184, \"blocks\": [{\"id\": \"0\", \"data\": {\"text\": \"\"}, \"type\": \"paragraph\"}], \"version\": \"2.23.1\"}"
          }
        },
        {
          "node": {
            "id": "UHJvZHVjdDoxMjc=",
            "name": "A Wie ABBA (Die Grössten Erfolge Von »Waterloo« Bis »Super Trouper«)",
            "description": "{\"time\": 1654858094989, \"blocks\": [{\"id\": \"0\", \"data\": {\"text\": \"\"}, \"type\": \"paragraph\"}], \"version\": \"2.23.1\"}"
          }
        },
        {
          "node": {
            "id": "UHJvZHVjdDoxMjY=",
            "name": "Eagle / Thank You For The Music",
            "description": "{\"time\": 1654858078996, \"blocks\": [{\"id\": \"0\", \"data\": {\"text\": \"\"}, \"type\": \"paragraph\"}], \"version\": \"2.23.1\"}"
          }
        }
      ]
    }
  },
  "extensions": {
    "cost": {
      "requestedQueryCost": 10,
      "maximumAvailable": 50000
    }
  }
}
```

#### Observações

- Permite a realização da conciliação contábil e financeira de forma automatizada
- Maior agilidade e eficiência operacional
- Integração com a automação comercial de vendas
- Segurança no recebiento das informações
- Atendimento Especializado