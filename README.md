![Desafio técnico | Estágio FrontEnd](https://res.cloudinary.com/das1rnjvi/image/upload/v1662943721/bluelogic/capa-desafio_ccpumj.png)

Conheça mais sobre a **[Bluelogic](https://www.bluelogic.com.br/)**

## Orientações

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

## Como funciona o desafio

Para nossa primeira etapa de avaliação técnica, propomos um teste onde o objetivo é compreender quais conhecimentos você já possui e sua desenvoltura diante a problemas ou tarefas que esteja se deparando pela primeira vez.


**Você deve seguir como base para o desenvolvimento do layout da aplicação o seguinte mockup:**
#### [ ► Mockup - Figma ](https://www.figma.com/file/r56MZpiRcB9fAEig5KefJn/Desafio-Flutter?node-id=0%3A1&t=n8x6hw8WjLztXMM3-1)

Com base no mockup do link acima você deve criar uma aplicação Front-end que consome a seguinte API : **[Blue API](https://tb7tsezd87.execute-api.eu-west-2.amazonaws.com/)**. Esta API contem dois métodos uma para autenticação e outro para uma lista de serviços.

### Payload da API

POST /auth

```json
{
   "user": "xx",
   "password": "xx"
}
```

GET /users

```json
{
   "user":"Fernando",
   "service_finish":100,
   "service_pending":20,
   "services":[
      {
         "company":"Empresa A",
         "location":"Rua XYZ",
         "status":"INICIADO"
      },
      {
         "company":"Empresa A",
         "location":"Rua XYZ",
         "status":"CANCELADO"
      },
      {
         "company":"Empresa A",
         "location":"Rua XYZ",
         "status":"CONCLUÍDO"
      },
      {
         "company":"Empresa BB",
         "location":"Rua XYZ",
         "status":"CONCLUÍDO"
      },
      {
         "company":"Empresa AA",
         "location":"Rua XYZ",
         "status":"CANCELADO"
      }
   ]
}
```

## 💽 Requisitos

A aplicação deve ser componentizada, com os seguintes componentes obrigatórios:

- ***Splash*** (Primeira interface a ser visualizada pelo usuário quando abrir o aplicativo);
- ***Login*** (Interface para login na aplicação);
- ***Home*** (Interface para visualizar os serviços, e alguns dados do usuário);

A aplicação deve seguir o mockup do figma.


## Como entregar o desafio

O desafio deve ser entregue no prazo máximo de **5 dias**, considerando que o prazo começa um dia depois do momento em que lhe enviamos as instruções.
Enviar para o e-mail **desenvolvimento@bluelogic.com.br** com o assunto `Desafio Técnico - [NOME DA CANDIDATO(A)]`.

*No Corpo do E-mail com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório

#### Como pré-requisito, o projeto não deve conter nenhum problema para executar a aplicação.

Caso tenha qualquer problema e não puder iniciar o desafio no prazo estabelecido, ou tiver dúvidas e dificuldades durante o processo, ou mesmo precisar de um feedback sobre sua avaliação, nos envie um e-mail e estaremos prontos para ajudar :)


Boa sorte! 🏆 🏆
