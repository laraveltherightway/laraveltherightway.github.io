---
title:  Table and Fields Naming
isChild: true
anchor:  table-fields-naming
---

##  Table and Fields Naming {#table-fields-naming}

### Table names MUST be in plural form and MUST be all lower-case

Good

```
class CreateFlightsTable extends Migration
{
    public function up()
    {
        Schema::create('flights', function (Blueprint $table) {
```

Bad

```
class CreateFlightsTable extends Migration
{
    public function up()
    {
        Schema::create('flight', function (Blueprint $table) {
```


```
class CreateUsersTable extends Migration
{
    public function up()
    {
        Schema::create('MyUsers', function (Blueprint $table) {
```

### Pivot table names MUST be in singular model names in alphabetical order

Good

```
post_user
article_user
photo_post
```

Bad
```
posts_users
user_articles
post_photos
```

### Table column names SHOULD be in snake_case without the model name

Good

```
username
title
thumb_url
```

Bad
```
UserName
_title
ThumbUrl
post_title
```

### Foreign keys MUST be singular model name with _id suffix

Good
```
user_id
```

Bad
```
userid
siteid
Memberid
TransactionID
```

### Primary Keys SHOULD be "id"

Good
```
id
```

Bad
```
ID
pkid
guid
```
