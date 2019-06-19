---
title:   The Ecosystem
isChild: true
anchor:  the-ecosystem
---

## The Ecosystem {#the_ecosystem}

At the very minimum, you need to know how to use [Git](https://git-scm.com/) and [Composer](https://getcomposer.org/). Though not required, it is better that you have an account on [GitHub.com](https://github.com/) as it is where all the code and its' dependencies are hosted.

For local development, you’ll need to have at least [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/) installed. This is used by [Homestead](https://laravel.com/docs/5.8/homestead) (a special vagrant box made for running Laravel apps). Although you can use the traditional WAMP/MAMP/XAMPP stack, those are not officially supported, thus you might have hard time down the road.

Pure “Laravel-way” frontend development might be a daunting one as it got has a long chain of technologies. You can either though [Laravel Blade](https://laravel.com/docs/5.8/blade) which is server-side templating or do client-side (browser), which at the very top of the chain is [Mix](https://laravel.com/docs/5.8/mix), a wrapper for [Webpack](https://webpack.js.org/). Webpack has its dependencies managed through [npm](https://www.npmjs.com/), all of which are packages of [NodeJS](https://nodejs.org/en/).



CSS is managed either through [Sass](http://sass-lang.com/) or [LESS](http://lesscss.org/), while JavaScript can be done through Plain JavaScript, [ReactJS](https://reactjs.org/) and the more common frontend framework used with Laravel: [VueJS](https://vuejs.org/).

For the backend stack, at the very least, you need a web server like [Nginx](http://nginx.org/), a php interpreter like [PHP-FPM](http://php-fpm.org/) and a database like [MySQL](https://www.mysql.com/). Other optional stack components are [Memcached](http://memcached.org/), [Redis](http://redis.io/) and [Beanstalkd](http://kr.github.io/beanstalkd/).

While you are not required to understand them all at once, it is advantagous that you are at least familiar with these and do some reading about what they are and where they are being used. This will save you tons of confusion when reading the documentation and references in the future.