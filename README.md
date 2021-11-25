# Seja bem vindo ou bem vinda.

<p>Resolvi criar esse tutorial de Sequelize para fortalecer nossa comunidade de devs. Espero que de ajude de alguma forma ;) </p>

## O que é o Sequelize?

<p>Sequelize é um ORM nodeJS que te ajuda a lidar de maneira mais simples com seus bancos de dados otimizando seu tempo de desenvolvimento, graças a sua sintaxe simples.</p>

## Fazendo as instalações necessárias

` npm i sequelize` ou `yarn add sequelize `

<p>Em seguida vamos instalar a CLI do sequelize globalmente com o comando:</p>

`yarn add sequelize -g` ou `npm i sequelize -g`

## Iniciando nosso projeto.

Crie sua pasta `src`, entre nela e dê o comando:

`sequelize init`

<p>Esse comando deverá ter criado algumas pastas dentro do seu projeto:</p>

<ul>
<li>config</li>
<li>migrations</li>
<li>models</li>
</ul>

## Configurações iniciais.

#### Começando pela segurança.

<p>Antes de qualquer coisa, vamos começar pelo que deve ser prioridade em qualquer projeto, mesmo que seja pra estudo: A segurança. <br> Existe até uma frase que diz "É de pequeno que se entorta o pepino". Então, não importa se é só um projeto simples para estudo.</p>

<p>Vamos instalar o <code>dotenv</code> para gerenciar nossas variáveis de ambiente e em seguida garantir que ele não vai ser enviado  pelo git: </p>

<code>yarn add dotenv -D</code> ou <code>npm i dotenv -D</code>

<p>Crie dentro da raiz do projeto um arquivo <code>.gitignore</code> e dentro dele escreva <code>.env</code>  (Vamos escrever a <code>node_modules</code> também, para que não esqueçamos).

Deve ficar dessa maneira:

```

node_modules
.env

```

Agora dentro do nosso dotenv, vamos criar nossas variáveis de ambiente:

<li><code>DATABASE=nome_da_sua_base_de_dados</code></li>
<li><code>DATABASE_HOSTNAME=host</code></li>
<li><code>DATABASE_PORT=porta</code></li>
<li><code>DATABSE_USERNAME=seu_username</code></li>
<li><code>DATABSE_PASSWORD=sua_senha</code></li>

<br>
