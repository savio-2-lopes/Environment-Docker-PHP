# Ambiente Docker PHP Apache MySQL

### Rodando o servidor
sudo docker compose up --build

### Criando projeto Laravel
composer create-project laravel/laravel .

### Ajustando erros de permissão
chmod -R 777 /var/www/php/