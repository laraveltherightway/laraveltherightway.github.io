---
title:   Production Environment
isChild: true
anchor:  production-environment
---

## Production Environment {#production-environment}


### You MUST regularly rotate your APP_KEY

APP_KEYS are set when you initialized a new Laravel application or executed the following command

```
php artisan key:generate 
```

> Laravel uses the key for all encrypted cookies, including the session cookie, before handing them off to the user's browser, and it uses it to decrypt cookies read from the browser. This prevents the client from making changes to their cookies and granting themselves admin privileges or impersonating another user in your application. Encrypted cookies are an important security feature in Laravel

From [APP_KEY And You](https://tighten.co/blog/app-key-and-you){:target="_blank"}