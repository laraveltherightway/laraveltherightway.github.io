---
title:   Environment Variables
isChild: true
anchor:  environment-variables
---

##  Environment Variables {#environment-variables}


### You MUST put sensitive information into .env files
Use .env files to store any secure information and retrieve it via __env__ function. There should be no instance on which you will put it inside models/controllers and commit it to Git.

Good
```
// .env 

API_HOST=https://example.com/api
API_USERNAME=myuser
API_PASSWORD=secret


// access the value from app/config.php file

return [
    ...
    'api_host' => env('API_HOST', 'https://defaultdomain.com')
    'api_username' => env('API_USER', 'defaultuser')
    'api_password' => env('API_USER', 'defaultpassword')
    ...
]

```


Bad
```
define('API_HOST', 'https://defaultdomain.com');
define('API_USERNAME', 'defaultuser');
define('API_PASSWORD', 'defaultpassword');

class DomainController extends Controller
{
    public function index()
    {
      $api_username   
    }

```



### your application key MUST be set. This is the APP_KEY variable in your .env file. You can generate one via 

```
php artisan key:generate
```
