# Locale

Each locale now resides in its own directory.

# Installation

## Composer

```json
{
  "require": {
    "croogo/locale": "2.0.x-dev"
  }
}
```

Add the following to `Config/bootstrap.php`

```php
<?php

App::build(array(
  'Locale' => array(APP . 'Vendor' . DS . 'croogo' . DS . 'locale' . DS ),
), App::APPEND);
```

# Tools

- Poedit (http://www.poedit.net/)
- Others http://www.gnu.org/software/gettext/manual/html_node/Editing.html#Editing
