yii2-rbac
=================

Yii2 Rbac

## Installation

The preferred way to install this extension is through composer.

Either run

```
php composer.phar require "giicms/yii2-rbac" "dev-master"
```
or add

```json
"giicms/yii2-rbac": "dev-master"
```

to the require section of your application's `composer.json` file.

## Usage Example
~~~php

 'modules' => [
        'rbac' => [
            'class' => 'giicms\rbac\Module',
        ],
  ],
~~~
