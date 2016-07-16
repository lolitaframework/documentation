Arr ( \MyProject\LolitaFramework\Core )
===
`Arr::accesible(mixed $value):bool`

Determine whether the given value is array accessible.

```php
$array = Arr::accessible(array('Some array value'));
// It's array. Function return true.

$string = Arr::accessible('Some string value');
// It's string. Function return false.
```


`Arr::add($array, $key, $value)`

The Arr::add function adds a given key / value pair to the array if the given key doesn't already exist in the array:
