\MyProject\LolitaFramework\Core\Route::typesConditions
===

Get types and conditions (`type => condition`). 


Example usage
---
```php
global $post;
var_dump(Route::typesConditions($post));

// array(23) {
//   ["some-taxonomy"]=>
//   object(Closure)#63 (1) {
//     ["static"]=>
//     array(1) {
//       ["tax_name"]=>
//       string(13) "some-taxonomy"
//     }
//   }
//   ["city"]=>
//   object(Closure)#64 (1) {
//     ["static"]=>
//     array(1) {
//       ["post_type"]=>
//       string(4) "city"
//     }
//   }
//   [404]=>
//   string(6) "is_404"
//   ["archive"]=>
//   string(10) "is_archive"
//   ["attachment"]=>
//   string(13) "is_attachment"
//   ["author"]=>
//   string(9) "is_author"
//   ["category"]=>
//   string(11) "is_category"
//   ["date"]=>
//   string(7) "is_date"
//   ["day"]=>
//   string(6) "is_day"
//   ["front"]=>
//   string(13) "is_front_page"
//   ["home"]=>
//   string(7) "is_home"
//   ["month"]=>
//   string(8) "is_month"
//   ["page"]=>
//   string(7) "is_page"
//   ["paged"]=>
//   string(8) "is_paged"
//   ["postTypeArchive"]=>
//   string(20) "is_post_type_archive"
//   ["search"]=>
//   string(9) "is_search"
//   ["single"]=>
//   string(9) "is_single"
//   ["sticky"]=>
//   string(9) "is_sticky"
//   ["singular"]=>
//   string(11) "is_singular"
//   ["tag"]=>
//   string(6) "is_tag"
//   ["tax"]=>
//   string(6) "is_tax"
//   ["time"]=>
//   string(7) "is_time"
//   ["year"]=>
//   string(7) "is_year"
// }
```
Return Value
---
**array**
