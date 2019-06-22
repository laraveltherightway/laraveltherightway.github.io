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

