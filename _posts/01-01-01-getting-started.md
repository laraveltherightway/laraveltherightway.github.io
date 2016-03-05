---
anchor: getting_started
---

# Getting Started {#getting_started_title}

## The Ecosystem

At the very minimum, you at least need to know how to use Git and Composer. Though not required, it is better that you have an account in GitHub.com as it is where all the codes and its dependencies is hosted.

For local development, you’ll need to have at least Vagrant and VirtualBox installed. This is used by Homestead (a special vagrant box made for running Laravel apps). Although you can use the traditional WAMP/MAMP/XAMPP stack, those are not officially supported, thus you might have hard time down the road.

Pure “Laravel-way” frontend development might be a daunting one as it got has a long chain of technologies. At the very top of the chain is Elixir, which is basically an API for GulpJS, which in turn requires npm which is basically a package manager for NodeJS.

CSS is managed either through SASS or LESS, while JavaScript is through CoffeeScript. You can write ES6/ES7 codes since Elixir also supports BabelJS. While NodeJS dependencies is then made available to browser through Browserify.

For backend stack, at the very least, you have Nginx, PHP-FPM and MySQL. Other optional stack component are Memcached, Redis and Beanstalkd.

While you are not required to understand them all at once. It is way better that you are at least familiar with the technologies that is going to be used, and at least do some reading what are those and where it is being used. This will save you tons of confusion when reading the documentation and references.
