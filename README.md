# TRABALHAR COM LARAVEL 5

## INSTALAÇÃO

### COMPOSER
- Baixar e instalar o composer: https://getcomposer.org/
- Criar uma pasta em seu servidor local e inicializar seu pront de comando favorito a partir dessa pasta
- Com o pront de comando inicializado, rodar o comando:<br>
<code>composer create-project laravel/laravel nm_project --prefer-dist</code>
- Será criado um novo projeto na estrutura Laravel 5

#### CONFIGURANDO DATABASE
- Configurar o arquivo <code>.env</code> que fica na raiz do projeto:<br>
<pre>
DB_HOST=localhost
DB_DATABASE= db_name
DB_USERNAME= db_username
DB_PASSWORD= db_password
</pre>

### INICIANDO APLICAÇÃO
- <code>php artisan serve</code>
- Acesse a aplicação em: http://localhost:8000


