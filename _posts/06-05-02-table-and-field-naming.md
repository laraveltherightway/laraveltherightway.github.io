---
anchor: table_and_field_naming
isChild: true
anchor:  table_and_field_naming
---

## Nomenclatura de tabela e campo {#table_and_field_naming_title}

Os nomes de tabelas e campos DEVEM estar em minúsculas e usar [Snake Case](https://en.wikipedia.org/wiki/Snake_case).

Nomes de tabelas devem usar a forma plural do objeto real que estão armazenando. Como por exemplo, o nome da tabela para postagens do blog deve ser * posts * not * post *.

Chaves primárias devem ser nomeadas "id" nos nomes das tabelas. Enquanto a chave estrangeira que representa em outra tabela deve estar no id de forma singular. (i.n. tabela: post, chave primária: id, chave estrangeira: post_id)
