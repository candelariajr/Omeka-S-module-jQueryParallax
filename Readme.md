# Readme
# jQueryParallax for Omeka S
Install as a normal Omeka-S module

This module does nothing on itself but provides [jQueryParallax] JS library for other modules
Refer to https://pixelcog.github.io/parallax.js/ for official API documentation

## Usage

Install and activate this module, then add the following to your templates:

```php
$this->headScript()->appendFile($this->assetUrl('parallax.min.js', 'jQueryParallax'));
```

[jQueryParallax]: https://pixelcog.github.io/parallax.js/
