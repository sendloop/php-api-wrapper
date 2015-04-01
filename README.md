# PHP wrapper class for Sendloop API v3

[![Latest Stable Version](https://poser.pugx.org/sendloop/sendloop/v/stable.svg)](https://packagist.org/packages/sendloop/sendloop) [![Monthly Downloads](https://poser.pugx.org/sendloop/sendloop/d/monthly.png)](https://packagist.org/packages/sendloop/sendloop) [![License](https://poser.pugx.org/sendloop/sendloop/license.svg)](https://packagist.org/packages/sendloop/sendloop)

For more details about API v3, please visit our help section at https://sendloop.com/help/api-001/getting-started

* [Installation](#installation)
* [Demo](#demo)
* [Documentation](#documentation)

## Installation
Simply add the package to your `composer.json` file and run `composer update`.

```
"sendloop/sendloop": "dev-master"
```

Or go to your project directory where the `composer.json` file is located and type:

```sh
composer require "sendloop/sendloop"
```

## Demo

```php
  $sendloop = new Sendloop\SendloopAPI3('YOUR_API3_KEY', 'SENDLOOP_SUBDOMAIN', 'json');
  $sendloop->run('List.GetList',array());

  print_r($sendloop->Result);
```

## Documentation

https://sendloop.com/help/api-001/getting-started
