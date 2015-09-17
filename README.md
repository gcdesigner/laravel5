# TRABALHAR COM LARAVEL 5

## INSTALAÇÃO

### COMPOSER
- Baixar e instalar o composer: https://getcomposer.org/
- inicialize seu pront de comando favorito a partir da pasta raiz do seu servidor local (www, htdocs, etc)
- Com o pront de comando inicializado, rodar o comando:<br>
<pre>composer create-project laravel/laravel <strong>nome_do_projeto</strong> --prefer-dist</pre>
- Será criado um novo projeto na estrutura Laravel 5

#### CONFIGURANDO DATABASE
- Configurar o arquivo <code>.env</code> que fica na raiz do projeto:<br>
<pre>
DB_HOST= localhost
DB_DATABASE= db_name
DB_USERNAME= db_username
DB_PASSWORD= db_password
</pre>

### INSTALANDO LARAVEL ELIXIR - Pre-processador de CSS e JS
- Ter o <strong>node.js</strong> instalado: http://nodejs.org/download/
- Instalar o <strong>Gulp</strong>: 
<pre>
npm install --global gulp
</pre>
- Instalar o Laravel Elixir:
<pre>
npm install
</pre>
- 

### INICIANDO APLICAÇÃO
- <code>php artisan serve</code>
- Acesse a aplicação em: http://localhost:8000


