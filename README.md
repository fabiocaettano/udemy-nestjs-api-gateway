<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Criar o projeto

```bash
$ nest new nomeDoProjeto
```

## NVM Gerenciador de Versão do Node
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

## Imagem do RabbitMQ disponiblizada pela Bitnami:
```bash
# Download da imagem
$ docker pull bitnami/rabbitmq:latest

# Executar o container
$ docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 bitnami/rabbitmq:latest

# Visualizar se o container está sendo executado
$ docker ps
```

Acessar o browser e digitar
http://localhost:15672

Credenciais padrão disponibilizada pela Bitnami:
Username: user
Password: bitnami

Virtual Host, informar o nome "smartranking" e clicar em Add virtual host.

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
