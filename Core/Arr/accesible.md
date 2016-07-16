\MyProject\LolitaFramework\Core\Arr::accesible
===
`Arr::accesible(mixed $value):bool`

Determine whether the given value is array accessible.

Example usage
---
```php
$array = Arr::accessible(array('Some array value'));
// It's array. Function return true.

$string = Arr::accessible('Some string value');
// It's string. Function return false.
```
Parameters
---
**$value** to check.

Return Value
---
**Boolean** true if value array accesible false if not.
