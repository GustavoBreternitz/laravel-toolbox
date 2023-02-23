## Laravel ToolBox
Repositório de testes para testes de diversas API's com foco em facilitar a vida humana por meio de BOT's

### Guia de Instalação:
Ao realizar o clone do repositório dentro da pasta /src rodar o seguinte comando:
```
composer install
```

Após isso corrigir o permissionamento das pastas de log com o comando:
```
sudo chmod 777 -R laravel-toolbox/src/storage/
```

Subir o projeto com docker-compose:
```
docker-compose up -d
```