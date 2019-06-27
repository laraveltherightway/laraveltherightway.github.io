---
title:  Database Alterations
isChild: true
anchor:  database-alterations
---

##  Database Alterations {#database-alterations}


### You MUST not be changing the database schema directly, use Database Migrations instead

Good
```
php artisan migrate
```

Bad

- use of PHPMyAdmin
- directly executing ALTER statement in mysql console / cli
- using sql file to change the db


### Migration filenames MUST follow to following pattern

creation of table
```
yyyy_mm_dd_<timestamp>_create_<table name>_table
```
Good

```
2019_06_06_164210_create_domains_table.php
```

Bad
```
2019_06_06_164210_domains.php
```