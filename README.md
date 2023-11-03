# Volg DB

Um simples ORM em PHP, utilizando PDO.

## Utilização


```php
<?php


require_once __DIR__ . '/vendor/autoload.php';


use VolgMvs\VolgDb\ModelBase;

class Pessoa extends ModelBase
{
    const TABLE_NAME = "pessoa";
}


$pessoa = new Pessoa();

```





