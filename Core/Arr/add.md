\MyProject\LolitaFramework\Core\Arr::add
===

The Arr::add function adds a given key / value pair to the array if the given key doesn't already exist in the array.
Example usage
---
```php
$array = Arr:add(['name' => 'Desk'], 'price', 100);

// ['name' => 'Desk', 'price' => 100]
```

Parameters
---
_array_ **$array**

_string_ **$key**

_mixed_ **$value**

Return Value
---
**Array** with new element.
