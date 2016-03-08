---
anchor: table_and_field_naming
isChild: true
anchor:  table_and_field_naming
---

## Table and field naming {#table_and_field_naming_title}

Table and field names MUST be lowercase and use [Snake Case](https://en.wikipedia.org/wiki/Snake_case).

Table name should use the plural form of the actual real life object it is storing. Like for example, the table name for blog posts should be *posts* not *post*.

Primary keys should be named "id" in the table names. While the foreign key it represents in other table should be on singularform_id. (e.g. table: post, primary key: id, foreign key: post_id )
