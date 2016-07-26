\MyProject\LolitaFramework\Core\Data::constants
===

Get all defined constants

Example usage
---
```php

define('SOME_CONSTANT', 'some constant value');

var_dump(Data::constants());

array(103) {

  ...
  
  ["SOME_CONSTANT"]=>
  string(19) "some constant value"
  
  ...
  
}

```

Return Value
---
__array__ all defined constants
