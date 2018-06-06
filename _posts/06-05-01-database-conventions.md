---
title: Convenções de banco de dados
anchor: database_conventions
---

# Convenções de banco de dados {#database_conventions_title}


### O Eloquent pode suportar múltiplos bancos de dados por um motivo - não se limite ao MySQL.

 Use [MongoDB](https://github.com/jenssegers/Laravel-MongoDB) para registros que possuem atributos que variam muito. Por exemplo, em um sistema de inventário, um produto de material de escritório pode ter um conjunto diferente de campos em comparação com suprimentos de veículo e de automóvel.

 Use [ElasticSearch](https://github.com/elasticquent/Elasticquent) para pesquisa e indexação de dados de alto volume.

 Use [Neo4J](https://github.com/Vinelab/NeoEloquent) para aplicativos que exigem relacionamentos complexos entre modelos. Por exemplo, um aplicativo de rede multinível, site de rede social e aplicativos semelhantes.
