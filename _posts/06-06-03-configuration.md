---
title: Configurando
anchor: configuration
---

# Configurando {#configuration_title}

Certifique-se sempre de que a sua chave de aplicativo esteja configurada. Esta é a variável APP_KEY no seu arquivo .env. Você pode gerar um via 

```
php artisan key:generate
```

Sempre dê um nome ao seu aplicativo. Ou seja, em vez de usar o namespace raiz _App_ padrão fornecido pelo Laravel install, defina-o como o aplicativo é. Isso pode ser definido via

```
php artisan app:name YourAppName
```

Isso faz com que seus controllers/models resolvam em YourAppName\Controllers e YourAppName\Models.

Use arquivos .env para armazenar qualquer informação segura e recuperá-la através da função getenv. Estas não devem ser nenhuma instância na qual você irá colocá-lo dentro de models/controllers e enviá-lo para o Git;