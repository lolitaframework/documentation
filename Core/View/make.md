\MyProject\LolitaFramework\Core\View::make
===

Render view. If `WP_DEBUG` is false function returns minimized code.

Example usage
---
```php

$view_full_path = View::make(
    '/Users/lf/sites/myproject/wp-content/themes/MyProject/app/views/view_name.php',
    array(
        'docs'      => 'Docs',
        'about_me'  => 'About me',
        'our_works' => 'Our works',
    )
);

// <ul>
//     <li>Docs</li>
//     <li>About me</li>
//     <li>Out works</li>
// </ul>

$view_full_path = View::make(
    'view_name',
    array(
        'docs'      => 'Docs',
        'about_me'  => 'About me',
        'our_works' => 'Our works',
    )
);

// <ul>
//     <li>Docs</li>
//     <li>About me</li>
//     <li>Out works</li>
// </ul>


```
Parameters
---
**$path** (string) (required) path to view file. You can specify the full path (like : `/Users/lf/sites/myproject/wp-content/themes/MyProject/app/views/view_name.php`) or just the view name ( like: `view_name`). The function will try to find our view file first in the default folder for views.

**$data** (array) (optional) data to put in view.

Return Value
---
**strin** HTML code.
