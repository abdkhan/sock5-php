
基于[swoole](https://github.com/swoole/swoole-src)扩展的sock5代理服务器

# Installation

Use [Composer](https://getcomposer.org/):

```sh
composer require liubinzh/sock5-php dev-master
```

# Usage
start.php

```php
<?php
require 'vendor/autoload.php';
use Liubinzh\Sock5\Sock5Server;

$s = new Sock5Server();
$s->start();
```

启动:

```sh

php  start.php -d

```