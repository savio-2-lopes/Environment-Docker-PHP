# Ambiente Docker PHP Apache MySQL



### Rodando o servidor
docker compose up --build

## Entre no terminal
docker exec -it php-apache bash

### Criando projeto Laravel
composer create-project laravel/laravel .

### Ajustando erros de permissão
chmod -R 777 /var/www/php/
