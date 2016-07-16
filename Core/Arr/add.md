\MyProject\LolitaFramework\Core\Arr::add
===
`Arr::add(array $array, string $key, mixed $value):array`

The add function adds a given key / value pair to the array if the given key doesn't already exist in the array.
Example usage
---
```php
$array = Arr:add(['name' => 'Desk'], 'price', 100);

// ['name' => 'Desk', 'price' => 100]
```

Parameters
---
[array] **$array**

[string] **$key**

[mixed] **$value**

Return Value
---
**Array** with new element.
