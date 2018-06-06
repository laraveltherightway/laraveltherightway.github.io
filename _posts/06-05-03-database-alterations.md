---
anchor: db_alterations
isChild: true
anchor:  db_alterations
---

## Alterar tabelas, indexar ou inserir dados de amostra. {#db_alterations}

NÃO crie tabelas ou indexe diretamente via PHPMyAdmin ou console. Use [database migration](https://laravel.com/docs/5.2/migrations#writing-migrations) para criar tabelas, adicionar / alterar campos e enviá-los para o repositório Git. 

NÃO passe diretamente a exportação do banco de dados (arquivos sql) para seus colegas para compartilhar suas alterações no banco de dados. Deixe-os executar os arquivos de migração que você confirmou no repositório.

Não insira valores falsos diretamente no banco de dados para fins de teste. Construa [Seeder](https://laravel.com/docs/5.2/seeding), arquivos para preencher seu banco de dados.