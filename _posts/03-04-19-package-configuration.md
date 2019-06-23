---
title:   Package Configuration
isChild: true
anchor:  package-configuration
---

##  Package Configuration {#package-configuration}

### Config and language files index SHOULD be in snake-case

Good
```
// config/myconfig.php
return [
    'my_api' => [
        'domain' => env('API_DOMAIN'),
        'secret' => env('API_SECRET'),
    ],
```

Bad
```
// config/myconfig.php
return [
    'MyApi' => [
        'DOMAIN' => env('API_DOMAIN'),
        'SECRET' => env('API_SECRET'),
    ],
```

> The best way to figure out if you have implemented best-practice in configuring your app, is if the codebase could be made open source at any moment without compromising any credentials