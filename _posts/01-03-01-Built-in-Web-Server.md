---
title:   Built-in Web Server
isChild: true
anchor:  builtin_web_server
---

## Built-in web server {#builtin_web_server_title}

You might notice a server.php in the Laravel codes. The purpose of this is for you to be able to run the project without even having a web server installed (e.g Apache or Nginx). This is primarily for development purpose only. This leverages the PHP 5.4's internal web server. You can use that by issuing either of the following commands:

{% highlight console %}
> php -S localhost:8000 server.php
{% endhighlight %}

or simply (note that the following **only** works for Laravel `v4.x`):

{% highlight console %}
> php artisan serve
{% endhighlight %}

You can also specify optional parameters

{% highlight console %}
> php artisan serve --port=8080 --host=local.dev
{% endhighlight %}
