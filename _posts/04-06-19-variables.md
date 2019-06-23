---
title:  Variables
isChild: true
anchor:  variables
---

##  Variables {#variables}

### General rule for variable is it SHOULD be in camelCase

Good
```
$articlesWithAuthor
```

Bad
```
$articles_with_author
```

### Collection names SHOULD be descriptive and in plural form

Good
```
$activeUsers = User::active()->get()
```

Bad
```
$users = User::active()->get()
$user = User::active()->get()
$User = User::active()->get()
```

### Single Object SHOULD be descriptive and in singular form

Good
```
$activeUser = User::active()->first()
```

Bad
```
$users = User::active()->first()
```