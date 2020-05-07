---
title:   Frontend Development
isChild: true
anchor:  frontend-development
---

## Frontend Development {#frontend_development}

Laravel can use a variety of frontend javascript frameworks. It also provides for frontend  presets (or ways to scaffold a frontend) which provides a basic starting point using [Bootstrap](https://getbootstrap.com/), [React](https://reactjs.org/), and / or [Vue](https://vuejs.org/).

### Auth Scaffolding 

Starting in laravel 6,  the artisan make:auth scaffolding has been moved to the `laravel/ui` package.

### Generating scaffolding

You can read more about generating scaffolding on the [docs/frontend](https://laravel.com/docs/7.x/frontend) page.


### Compiling Assets

Everytime you add a new component to your app.js file, you need run `npm run dev` to compile the new component into javascript. To develop while automatically reloading your page everytime you change a frontend file, you can run `npm run watch`.  For more information on how to configure laravel mix to compile different types of assets, please checkout the docs on [compiling assets](https://laravel.com/docs/7.x/mix#installation).


### CORS requests 

When developing a Single Page Application with laravel as the backend, you have to setup your middleware to accept [CORS  request](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS). Laravel 7 introduced [native support for CORS](https://laravel.com/docs/7.x/routing#cors), but if you are on an earlier version of laravel, you can use [spatie/laravel-cors](https://github.com/spatie/laravel-cors) to allow for requests to push through. You can learn about CORS [here](https://httptoolkit.tech/will-it-cors/).

### CSRF Token

When developing your [SPA](https://flaviocopes.com/single-page-application/), you may still want to secure your application's forms with Laravel's default CSRF Tokens.  To do so, you'll need to attach the CSRF token to your form requests. You can do this by adding the value of the `X-XSRF-TOKEN` header. If you are building the SPA separately from your laravel app, you might want to use api-tokens instead. In Laravel 7, you can use [Laravel Sanctum's API Token Authentication](https://laravel.com/docs/7.x/sanctum#api-token-authentication) for this.

### Additional Resources

- [Video: Frontend Scaffolding Has Been Moved to Laravel UI](https://laracasts.com/series/whats-new-in-laravel-6/episodes/3)
- [Video: Learn Vue 2: Step By Step](https://laracasts.com/series/learn-vue-2-step-by-step)
- [Tutorial: Build authentication into your Laravel API with JSON Web Tokens (JWT)](https://medium.com/employbl/build-authentication-into-your-laravel-api-with-json-web-tokens-jwt-cd223ace8d1a)


