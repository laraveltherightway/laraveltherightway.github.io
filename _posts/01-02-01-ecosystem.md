---
title:   O Ecossistema
isChild: true
anchor:  the-ecosystem
---

## O Ecossistema {#the_ecosystem}

No mínimo, você precisa saber usar [Git](https://git-scm.com/) e [Composer](https://getcomposer.org/). 
Embora não seja obrigatório, é melhor que você tenha uma conta no [GitHub.com](https://github.com/), é onde todo o código e suas dependências são hospedadas.

Para o desenvolvimento local, você precisará ter pelo menos [Vagrant](https://www.vagrantup.com/) e [VirtualBox](https://www.virtualbox.org/) instalados. Isto é usado por [Homestead](https://laravel.com/docs/5.2/homestead) (Uma caixa especial Vagrant para rodar aplicações Laravel). Embora você possa usar a pilha tradicional de WAMP / MAMP / XAMPP, eles não são oficialmente suportados, portanto, você pode ter dificuldades ao longo do caminho.

O puro “caminho Laravel” para desenvolvimento frontend pode ser assustador, pois tem uma longa cadeia de tecnologias. No topo da cadeia está [Elixir](https://laravel.com/docs/5.2/elixir), que é basicamente uma API para [GulpJS](http://gulpjs.com/), que por sua vez requer [npm](https://www.npmjs.com/) que é basicamente um gerenciador de pacotes para o [NodeJS](https://nodejs.org/en/).

CSS é gerenciado através de [Sass](http://sass-lang.com/) ou [LESS](http://lesscss.org/), enquanto JavaScript através de [CoffeeScript](http://coffeescript.org/). Você pode escrever códigos [ES6/ES7](http://es6-features.org/) desde que sejam suportados pelo Elixir [BabelJS](https://babeljs.io/). Enquanto  as dependências NodeJS são disponibilizadas aos navegadores pelo [Browserify](http://browserify.org/).

Para a pilha de backend, no mínimo, você precisa de um servidor web como [Nginx](http://nginx.org/), um interpretador PHP como [PHP-FPM](http://php-fpm.org/) e um banco de dados como [MySQL](https://www.mysql.com/). Outros componentes opcionais são [Memcached](http://memcached.org/), [Redis](http://redis.io/) e [Beanstalkd](http://kr.github.io/beanstalkd/).

Enquanto você não é obrigado a entendê-los todos de uma vez, é vantajoso que você esteja, pelo menos, familiarizado com estes e faça algumas leituras sobre o que eles são e onde eles estão sendo usados. Isso economizará toneladas de confusão ao ler a documentação e as referências no futuro.

