# nuxt-fy-crud-laravel-api

#### Tecnologias:

Nuxt e Vuetify (front)
Laravel Api (back)

#### Objetivo:

Um Painel Administrativo com Cadastro, Edição, Exclusão e Listagem
de Produtos e Categorias e
Página Inicial que mostra os Produtos com Imagens

---

##### Print das telas do projeto

<p align="center"><img src="prints/1.png" >
</p>

<p align="center"><img src="prints/2.png" >
</p>

<p align="center"><img src="prints/3.png" >
</p>

<p align="center"><img src="prints/4.png" >
</p>

<p align="center"><img src="prints/5.png" >
</p>

### Requisitos:

+ composer

+ npm 

+ php >= 7.3

+ mysql ou mariab

+ apache ou nginx

#### Configurando o Backend:

+ Abra a pasta back 

```bash
composer install
```

```bash
cp .env.example .env
```
+ Configure as variaveis de Banco de dados no arquivo .env para configuração das tabelas (configure um Banco para fins de teste)

```bash
php artisan key:generate
```

```bash
php artisan migrate:fresh --seed
```

```bash
php artisan serve
```

+ Deixe o servidor rodando

2. Execute os comandos a seguir para as configurações de frontend:

#### Configurando o Frontend:

+ Abra um novo terminal de linha de comando e acesse a pasta front

```
yarn install
```

##### Compiles and hot-reloads for development
```
yarn serve
```

##### Compiles and minifies for production
```
yarn build
```

##### Lints and fixes files
```
yarn lint
```

##### Crie um arquivo .env a partir de .env.example
```
coloqe a url da api (url do servidor do laravel) em URL_API
digite o nome do projeto em PROJECT_NAME
```

##### Compile e Rode 
```
npm run dev

ou

npm run build (para producao)
```

##### Caso tenha problemas com instalação do projeto envie um email para:
```
lucianopalharesrosa@hotmail.com
```

