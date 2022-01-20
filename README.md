<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Criar o projeto

```bash
$ nest new nomeDoProjeto
```

## NVM Gerenciador do Node
Checar as versões instaladas:
````bash
$ nvm ls
````

Instalar a versão 12.18.3:
````bash
$ nvm install v12.18.3
````

Para trocar a versão:
````bash
$ nvm use v14.17.0
````

## Dependências do Projeto
```bash
$ npm install @nestjs/microservices
$ npm install amqplib amqp-connection-manager
$ npm install moment-timezone
$ npm install class-validator class-transformer
```

## Executar o projeto:

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Licença

Nest is [MIT licensed](LICENSE).
