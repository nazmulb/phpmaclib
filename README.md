# mac-address-php
A library to get MAC Address using PHP

***Author:*** Md. Nazmul Basher
***Email:*** nazmul.basher@gmail.com

## Installation

```js
composer require nazmulb/mac-address-php dev-master
```

## Example

```php
<?php
require_once __DIR__ . '/vendor/autoload.php';

use \NazmulB\MacAddressPhpLib\MacAddress;

echo MacAddress::getMacAddress();
```