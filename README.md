# Gestão de séries

Sistema de gestão de séries, com ele é possivel cadastrar uma série, suas temporadas, episódios, marca-los como assistidos...

### Build do Sistema

Siga os passos abaixo para configurar e executar o projeto localmente:

1. **Clonar o Repositório:**

2. ### Requisitos

- PHP 8.1 ou superior
- Composer 2.2 ou superior
- O projeto esta no Laravel na versao 10.48.10

3. ### Instalação de Dependências

   composer install
   
   npm install
   
5. ### Configuração do Ambiente
    cp .env.example .env

Copie o arquivo .env.example para .env e configure as variáveis de ambiente, como conexão com banco de dados.


5. ### Migrations e seeders

   php artisan migrate

   Executa as migrations de tabelas para o banco de dados

   php artisan db:seed

   Roda as seeders e popula as tabelas Categorias e Situacoes no banco de dados

6. ### Execucao do projeto
   php artisan serve

   o projeto estará disponivel em http://localhost:8000 que é a porta padrao
