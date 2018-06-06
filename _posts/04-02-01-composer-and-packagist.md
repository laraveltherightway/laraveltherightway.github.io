---
isChild: true
anchor:  composer_and_packagist
---

## Composer e Packagist {#composer_and_packagist_title}

Por padrão, o Packagist é usado como um repositório de pacotes e o GitHub para baixar os arquivos em si. Mas você pode definir seus próprios repositórios configurando os espelhos de pacotes, [Satis][satis]. Embora você possa usar qualquer classe ou funções simples do PHP dentro do Laravel (contanto que ele possa ser carregado automaticamente). Essa não é uma pratica recomendada. Faça sua própria [Biblioteca Composer][own-composer] para cada conjunto específico de classes de aplicativo e incluí-lo como uma dependência no arquivo composer.json.

[satis]:https://getcomposer.org/doc/articles/handling-private-packages-with-satis.md
[own-composer]:http://knpuniversity.com/screencast/question-answer-day/create-composer-package