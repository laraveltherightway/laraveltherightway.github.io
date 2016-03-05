---
isChild: true
anchor:  composer_and_packagist
---

## Composer and Packagist {#composer_and_packagist_title}

By default, it is using Packagist as repository and GitHub to download the files itself. But you can define your own repositories by setting up your own [Satis][satis] mirror of packages. Although you can use any class or even plain php functions inside Laravel (as long as it can be autoloaded). This is not a recommended practice. Make your own [Composer library][own-composer] for each application specific classes and include it as a dependency in the composer.json file.

[satis]:https://getcomposer.org/doc/articles/handling-private-packages-with-satis.md
[own-composer]:http://knpuniversity.com/screencast/question-answer-day/create-composer-package