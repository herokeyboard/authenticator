# Authenticator
## Installation

```
composer require herokeyboard/authenticator:dev-main
```

## Usage

```php
require_once ('vendor/autoload.php');
use \Herokeyboard\Authenticator;
$Authen = new Authenticator();
$result = $Authen->code("XXIIAJ6JUFQV5ED636Z6DHYXS3QWKRXX");
print_r($result);
```
