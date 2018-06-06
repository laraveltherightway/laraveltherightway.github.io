---
anchor: right-database-choice
isChild: true
anchor:  right-database-choice
---

## Escolha o banco de dados certo para o trabalho em questão. {#right-database-choice}

O Eloquent pode suportar múltiplos bancos de dados por uma razão - não se limite ao MySQL.

 Use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB) para registros que possuem atributos que variam muito. Por exemplo, em um sistema de inventário, um produto de material de escritório pode ter um conjunto diferente de campos em comparação com suprimentos de veículo e de automóvel.

 Use [ElasticSearch](https://github.com/elasticquent/Elasticquent) para pesquisa e indexação de dados de alto volume. Também é útil em sistemas que exigem fragmentação de dados em várias máquinas, o que é muito grande para caber em uma única réplica.

 Use [Neo4J](https://github.com/Vinelab/NeoEloquent)para aplicativos que exigem relacionamentos complexos entre modelos. Por exemplo, um aplicativo de rede multi-nível, site de rede social e similares. Embora você possa fazer o mesmo no MySQL, a quantidade de junções quando você vai além dos relacionamentos pai-filho de 2 níveis será insuportável em qualquer ambiente de produção.