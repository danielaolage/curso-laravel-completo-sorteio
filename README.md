# Curso laravel completo sorteio

Repositório com a aplicação desenvolvida para sortear os brindes do curso de laravel fornecido pelo Webschool.io

# Quer ganhar o primeiro livro sobre certificaçao PHP totalmente em português? E que tal uma camiseta do curso de laravel? Ou melhor você pode ter os dois!

Para concorrer aos prêmios basta seguir os seguintes passos:

1. Se envolva no projeto (Dê sua opnião, divulgue e ajude a gente a evoluir também)
2. Dê um favorito no projeto aqui no github
3. Convide o seu amigo acessando http://cursolaravel.webschool.io/ (Para concorrer efetivamente o seu amigo deve confirmar o e-mail que ele receberá sobre o curso)

Com isso você ja está dentro do sorteio, é só esperar e torcer.

# Aprenda com esse repositório também

Como estamos fazendo um curso de laravel nada mais justo do que criarmos aplicações reais com o laravel, não é mesmo ?

Esse repositório apesar de possuir uma aplicação simples possui alguns conceitos muito interessantes:

1. A utilização da abstração de envio de e-mail que o laravel nos fornece
2. A utilização do elixir para gerenciar os nossos assets
3. A utilização de migrations para as tabelas do banco de dados

## Fique antenado

O nosso canal do slack é junto com o do da webschool.io, então acesse https://webschoolbr.slack.com e procure pelo canal **curso-laravel**

![Slack](http://s12.postimg.org/ynqtaqpql/slack.png)

# Quer mais ?

O curso oficial de laravel você confere em https://github.com/Webschool-io/Curso-PHP-Laravel-Completo-E-Total

# Começando

A primeira coisa que devemos fazer é clonar o repositório

```
git clone https://github.com/marabesi/curso-laravel-completo-sorteio.git && cd curso-laravel-completo-sorteio
```

O segundo passo e configurar o seu **.env** para que se conecte corretamente no banco de dados, veja uma configuraçao simples a seguir como exemplo

```
DB_DATABASE=curso_laravel
DB_USERNAME=postgres
DB_PASSWORD=123456
APP_ENV=development
APP_DEBUG=true
```

Agora o que precisamos fazer é executar as migrations para que seja executado os scripts para subir a estrutura de banco de dados

```
php artisan migrate
```

A seguinte resposta deve ser exibida ao executar o script acima

```
Migration table created successfully.
Migrated: 2016_03_05_221433_TabelaDe
Migrated: 2016_03_05_222233_TabelaPara
Migrated: 2016_03_05_224832_TabelaConvite
```

O último passo é executar o servidor embutido que o laravel fornece para nós e acessar a nossa aplicação
em um navegador qualquer

```
php artisan serve
```

Abra seu navegador e acesse o endereço **http://localhost:8000** e divirta-se !