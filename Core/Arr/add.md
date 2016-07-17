\MyProject\LolitaFramework\Core\Arr::add
===

The Arr::add function adds a given key / value pair to the array if the given key doesn't already exist in the array.
Example usage
---
```php
$array = Arr:add(['name' => 'Desk'], 'price', 100);

// ['name' => 'Desk', 'price' => 100]
```

```php
$array = Arr:add(
    [
        'name' => 'John Doe',
        'age'  => 32,
    ],
    'age',
    '25'
);

// ['name' => 'John Doe', 'age' => 32]
```

```php
$array = Arr:add(
    [
        'name' => 'John Doe',
        'age'  => 32,
    ],
    'kids.0',
    ['name' => 'Baby Doe', 'age' => 1]
);

// [
//    'name' => 'John Doe',
//    'age'  => 32,
//    'kids' => [
//        [
//            'name' => 'Baby Doe',
//            'age'  => 1
//        ]
//    ]
// ]
```

Parameters
---
_array_ **$array**

_string_ **$key**

_mixed_ **$value**

Return Value
---
**Array** with new element.
