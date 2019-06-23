---
title:   Controllers
isChild: true
anchor:  controllers
---

##  Controllers {#controllers}

### Controller name MUST start with a noun (in singular form) followed by the word "Controller".

**Good** 

```
class ArticleController extends Controller
{
```

**Bad**

```
class ArticlesController extends Controller
{
```

```
class wp_articlesController extends Controller
{
```

```
class Article extends Controller
{
```

## Use Resource Controllers unless you have any particular reason not to do so

Good
```
class DomainController extends Controller
{
    public function index(){} // list domains
    public function create(){} // show create form
    public function store(Request $request){ } // handle the form POST 
    public function show($id){} // show a single domain
    public function edit($id){} // show edit page
    public function update(Request $request, $id){} // handle show edit page POST
    public function destroy($id){} // delete a domain
}
```


Bad

```
class DomainController extends Controller
{
    public function list(){} // list domains
    public function create_or_save(){} // show create form then handle save
    public function show_edit($id){} // show a single domain then show edit page
    public function delete($id){} // delete a domain
}
```

