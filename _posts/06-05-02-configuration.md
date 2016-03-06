---
anchor: configuration
---

# Configuration {#configuration_title}

Always make sure your application key is set. This is APP_KEY variable in .env file. You can generate one via 

```
php artisan key:generate
```


Always give your application a name. That is, instead of using the default _App_ root namespace given by Laravel install, set it to what the application is all about. This can be set via 

```
php artisan app:name YourAppName
```

This makes your controllers/models etc resolve into YourAppName\Controllers and YourAppName\Models.

Use .env files to store any secure information and retrieve it via getenv function. These should be no instance on which you will put it inside models/controllers and commit it to Git.