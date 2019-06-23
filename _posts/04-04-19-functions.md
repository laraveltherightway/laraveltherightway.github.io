---
title:  Functions
isChild: true
anchor:  functions
---

##  Functions {#functions}

Laravel comes with a lot of useful helper functions, but you can also define your own helper functions, given the following conditions:

### You SHOULD place your custom helper functions by creating a file called helper.php

Good
```
project_folder/app/helper.php
project_folder/app/Http/helper.php
```

Bad
```
project_folder/functions.php
```

### You MUST use Composer's autolading capability to load your functions

Good
```
// file composer.json
...
"autoload": {
    "files": [
        "app/helpers.php"
    ],
...
```

Bad
```
// file app/Http/Controllers/HomeController.php

class HomeController.php
{
    function index(){
        require_once(app_path("helpers.php"));
    }
}

```

### You MUST check if the the function exists before defining it

Good
```
if (! function_exists('my_custom_helper')) {
    function my_custom_helper($key, $default = null) {
        // ...
    }
}
```

Bad
```
function my_custom_helper($key, $default = null) {
    // ...
}
```
### Other General guides with functions

- If the function lenght exceeds 25 lines, you SHOULD break it down to multiple functions
- Each function SHOULD have a __Unit Test__ associated with it


