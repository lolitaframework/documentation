\MyProject\LolitaFramework\Core\Route::type
===

Get active route type.


Example usage
---
```php
// Route: /2016/07/16/hello-world/

var_dump(\MyProject\LolitaFramework\Core\Route::type());

// single
```

```php
// Route: /wrong_url

var_dump(\MyProject\LolitaFramework\Core\Route::type());

// 404
```
Return Value
---
**string**
