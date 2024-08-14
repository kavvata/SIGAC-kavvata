## SIGAC

Sistema de Gerenciamento das Atividades Complementares. Projeto para o desenvolvimento das atividades da disciplina de DW-II, IFPR 2024.

## Requisitos de Sistema
- PHP Versão: 8.1
- Laravel Versão: 10.29
- Docker Versão:  27.1

## Como Testar
- cp .env.example .env
- composer install
- php artisan sail:install
- ./vendor/bin/sail artisan key:generate
- ./vendor/bin/sail up

