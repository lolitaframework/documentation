\MyProject\LolitaFramework\Core\View::minimize
===

Minimize HTML code before output.

Example usage
---
```php

return View::minimize(
    "<h1>Hello</h1>".
    "\n".
    "<span>Lolita Framework is fucking awesome</span>"
);

// <h1>Hello</h1><span>Lolita Framework is fucking awesome</span>


```
Parameters
---
**$path** (string) (required) path to view file. You can specify the full path (like : `/Users/lf/sites/myproject/wp-content/themes/MyProject/app/views/view_name.php`) or just the view name ( like: `view_name`). The function will try to find our view file first in the default folder for views.

**$data** (array) (optional) data to put in view.

Return Value
---
**strin** HTML code.
