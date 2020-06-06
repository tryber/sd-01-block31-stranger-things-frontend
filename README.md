# Boas vindas ao repositório frontend do projeto de Deploy - Stranger Things!

Aqui você vai encontrar os locais para colocar suas repostas relativas aos requisitos de frontend.

**Lembre-se**: coloque as respostas apenas dos requisitos que contém o seguinte direcionamento:

  - Adicione os comandos utilizados, de maneira sequencial, ao README do frontend.

**Nota**: Este direcionamento está presente no [repositório](https://github.com/tryber/sd-01-block31-stranger-things) em que os requisitos do projeto são destrinchados.

## Requisitos

### 9 - Deploy Heroku

Para realizar o deploy do meu frontend, fiz o seguinte procedimento:

`heroku create project-stranger-things-1229 --buildpack mars/create-react-app`

`heroku config:set REACT_APP_HAWKINGS=https://deploy-backend-hawkings-1229.herokuapp.com/ REACT_APP_UPSIDEDOWN=https://deploy-backend-upsidedown-1229.herokuapp.com/`

`git add .`

`git commit -m "Iniciando deploy no projeto frontend"`

`git push stranger-things gabriel-coruja-stranger-things-frontend:master`

## Bônus

### 10 - Multi-ambientes

Para tornar a minha a minha aplicação Multi-ambiente, fiz o seguinte procedimento:

`Adicione aqui os comandos utilizados, de maneira sequencial.`
