# DVPP (Damn vulnerable PHP Package)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fswschmidt%2FDVPP.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fswschmidt%2FDVPP?ref=badge_shield)


### WARNING: DO NOT ATTEMPT TO INSTALL THIS PACKAGE. IT'S MADE FOR TESTING PURPOSE.

### Install via composer

Add `shieldfy/DVPP` to composer.json configuration file.
```
$ composer require shieldfy/DVPP
```

And update the composer
```
$ composer update
```
    
## Get joke by username
```php
require 'vendor/autoload.php';

use Shieldfy\DVPP;

$results = DVPP::getJokeByUsername();
```
`/index.php?username=jak`

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fswschmidt%2FDVPP.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fswschmidt%2FDVPP?ref=badge_large)