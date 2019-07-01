---
title:   The Ecosystem
isChild: true
anchor:  the-ecosystem
---

## The Ecosystem {#the_ecosystem}

At the very minimum, you need to know how to use [Git](https://git-scm.com/){:target="_blank"} and [Composer](https://getcomposer.org/){:target="_blank"}. Though not required, it is better that you have an account on [GitHub.com](https://github.com/){:target="_blank"} as it is where all the code and its dependencies are hosted.

You MUST be comfortable in using [Command Line Interface (CLI)](https://en.wikipedia.org/wiki/Command-line_interface){:target="_blank"}, specially Unix Shells (sh, ksh, csh, tcsh, bash etc) as it is heavily used for common tasks in working with Laravel.

For local development, you’ll need to have at least [Vagrant](https://www.vagrantup.com/){:target="_blank"} and [VirtualBox](https://www.virtualbox.org/){:target="_blank"} installed. This is used by [Homestead](https://laravel.com/docs/5.8/homestead){:target="_blank"} (a special vagrant box made for running Laravel apps). Although you can use the traditional WAMP/MAMP/XAMPP stack, those are not officially supported, thus you might have hard time down the road.

Pure “Laravel-way” frontend development might be a daunting one as it got has a long chain of technologies. You can either use [Laravel Blade](https://laravel.com/docs/5.8/blade){:target="_blank"} which is server-side templating or do client-side (browser), which at the very top of the chain is [Mix](https://laravel.com/docs/5.8/mix){:target="_blank"}, a wrapper for [Webpack](https://webpack.js.org/){:target="_blank"}. Webpack has its dependencies managed through [npm](https://www.npmjs.com/), all of which are packages of [NodeJS](https://nodejs.org/en/){:target="_blank"}.

CSS is managed either through [Sass](http://sass-lang.com/){:target="_blank"} or [LESS](http://lesscss.org/){:target="_blank"}, while JavaScript can be done through Plain JavaScript, [ReactJS](https://reactjs.org/){:target="_blank"} and the more common frontend framework used with Laravel: [VueJS](https://vuejs.org/){:target="_blank"}.

For the backend stack, at the very least, you need a web server like [Nginx](http://nginx.org/){:target="_blank"}, a php interpreter like [PHP-FPM](http://php-fpm.org/){:target="_blank"} and a database like [MySQL](https://www.mysql.com/){:target="_blank"}. Other optional stack components are [Memcached](http://memcached.org/){:target="_blank"}, [Redis](http://redis.io/){:target="_blank"} and [Beanstalkd](http://kr.github.io/beanstalkd/){:target="_blank"}.

While you are not required to understand them all at once, it is advantagous that you are at least familiar with these and do some reading about what they are and where they are being used. This will save you tons of confusion when reading the documentation and references in the future.