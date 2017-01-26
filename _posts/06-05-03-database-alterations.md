---
anchor: db_alterations
isChild: true
anchor:  db_alterations
---

## Changing tables, index or inserting sample data. {#db_alterations}

DON'T create tables or index directly via PHPMyAdmin or console. Use [database migration](https://laravel.com/docs/5.2/migrations#writing-migrations) to create table, add/alter any fields, and commit those to Git repository. 

DON'T directly pass the database export (sql files) to your colleagues in order to share your database changes. Let them run the migration files you committed to the repository.

DON'T insert fake values directly into the database for testing purposes. Create [Seeder](https://laravel.com/docs/5.2/seeding) files to populate your database.