# Boas vindas ao repositório frontend do projeto de Deploy - Stranger Things!

Aqui você vai encontrar os locais para colocar suas repostas relativas aos requisitos de frontend.

**Lembre-se**: coloque as respostas apenas dos requisitos que contém o seguinte direcionamento:

  - Adicione os comandos utilizados, de maneira sequencial, ao README do frontend.

**Nota**: Este direcionamento está presente no [repositório](https://github.com/tryber/sd-01-block31-stranger-things) em que os requisitos do projeto são destrinchados.

## Requisitos

### 9 - Deploy Heroku

Para realizar o deploy do meu frontend, fiz o seguinte procedimento:

-`heroku create --remote strangerthings stranger-things-frontend --buildpack mars/create-react-app`

-`heroku config:set REACT_APP_TIMEOUT="30000" --app stranger-things-frontend`

-`heroku config:set REACT_APP_HAWKINGS="https://deploy-backend-hawkings-4566.herokuapp.com/" --app stranger-things-frontend`

-`heroku config:set REACT_APP_UPSIDEDOWN="https://deploy-backend-upsidedown-4566.herokuapp.com/" --app stranger-things-frontend`

-`git add .`

-`git commit -m "deploy frontend"`

-`git push strangerthings conradomedeirosdev-sd-01-block31-stranger-things-frontend:master`

## Bônus

### 10 - Multi-ambientes

Para tornar a minha a minha aplicação Multi-ambiente, fiz o seguinte procedimento:

`Adicione aqui os comandos utilizados, de maneira sequencial.`
