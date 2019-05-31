---
anchor: naming_conventions
isChild: true
---

### Controller Names

Controller name must be a singular form.

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

**Horrible**

```
class wp_articlesController extends Controller
{
```