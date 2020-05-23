# Boas vindas ao repositório frontend do projeto de Deploy - Stranger Things!

Aqui você vai encontrar os locais para colocar suas repostas relativas aos requisitos de frontend.

**Lembre-se**: coloque as respostas apenas dos requisitos que contém o seguinte direcionamento:

  - Adicione os comandos utilizados, de maneira sequencial, ao README do frontend.

**Nota**: Este direcionamento está presente no [repositório](https://github.com/tryber/sd-01-block31-stranger-things) em que os requisitos do projeto são destrinchados.

## Requisitos

### 9 - Deploy Heroku

Para realizar o deploy do meu frontend, fiz o seguinte procedimento:

- `heroku create --remote stranger-things project-stranger-things-1223 --buildpack mars/create-react-app`

- `heroku config:set REACT_APP_HAWKINGS=https://deploy-backend-hawkings-1223.herokuapp.com`
- `heroku config:set REACT_APP_UPSIDEDOWN=https://deploy-backend-upsidedown-1223.herokuapp.com`
- `heroku config:set REACT_APP_TIMEOUT=30000`

- `git add .`
- `git commit -m "Iniciando deploy no projeto frontend"`
- `git push stranger-things gabriel-coruja-stranger-things-frontend:master`


## Bônus

### 10 - Multi-ambientes

Para tornar a minha a minha aplicação Multi-ambiente, fiz o seguinte procedimento:

- `git remote rename stranger-things development`
- `heroku create --remote production project-stranger-things-1224 --buildpack mars/create-react-app`

- `git add .`
- `git commit -m "Iniciando novo deploy no projeto frontend"`
- `git push development gabriel-coruja-stranger-things-frontend:master`

- `heroku config:set REACT_APP_HAWKINGS=https://deploy-backend-hawkings-1223.herokuapp.com --app project-stranger-things-1224`
- `heroku config:set REACT_APP_UPSIDEDOWN=https://deploy-backend-upsidedown-1223.herokuapp.com --app project-stranger-things-1224`
- `heroku config:set REACT_APP_TIMEOUT=30000 --app project-stranger-things-1224`

- `git push production gabriel-coruja-stranger-things-frontend:master`

### 11 - Development Mode

Segue o link para o projeto em desenvolvimento
Segue o link para o projeto em produção
