Economizzer
=================================

Economizzer is a simple and open source personal finance manager app made in PHP (Yii Framework 2.0).

For now only available in **english** and **portuguese (Brazilian)**

![Screnn](https://raw.github.com/gugoan/economizzer/master/web/images/screen.png)



Requirements
------------

The minimum requirement by this application that your Web server supports PHP 5.4.0.


Installation
------------

### Composer way: 
~~~
git clone https://github.com/gugoan/economizzer.git
cd economizzer
composer require "fxp/composer-asset-plugin:~1.0"
~~~

### Zip way:

soon..


Configuration
-------------

Create the **economizzer** database and import the file **economizzer.sql**.

In folder **economizzer/config/db.php**

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=economizzer',
    'username' => 'root',
    'password' => '',
    'charset' => 'utf8',
    'tablePrefix' => 'tb_',
    'enableSchemaCache' => true,
];
```

Access **http://economizzer/web** with user and password below:

User: joe

Pass: 123456

-------------

[![Yii2](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](http://www.yiiframework.com/)
