---
anchor: naming_conventions
isChild: true
---

### Controller Names

Controller name must start with a noun (in singular form) followed by the word "Controller".

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
