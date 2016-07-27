\MyProject\LolitaFramework\Core\Route::base
===

Get base route info: type, condition, template callback.

Example usage
---
```php
var_dump(Route::base());

// array(21) {
//   [0]=>
//   array(3) {
//     ["type"]=>
//     string(3) "404"
//     ["condition"]=>
//     string(6) "is_404"
//     ["template"]=>
//     string(16) "get_404_template"
//   }
//   [1]=>
//   array(3) {
//     ["type"]=>
//     string(7) "archive"
//     ["condition"]=>
//     string(10) "is_archive"
//     ["template"]=>
//     string(20) "get_archive_template"
//   }
//   [2]=>
//   array(3) {
//     ["type"]=>
//     string(10) "attachment"
//     ["condition"]=>
//     string(13) "is_attachment"
//     ["template"]=>
//     string(23) "get_attachment_template"
//   }
//   [3]=>
//   array(3) {
//     ["type"]=>
//     string(6) "author"
//     ["condition"]=>
//     string(9) "is_author"
//     ["template"]=>
//     string(19) "get_author_template"
//   }
//   [4]=>
//   array(3) {
//     ["type"]=>
//     string(8) "category"
//     ["condition"]=>
//     string(11) "is_category"
//     ["template"]=>
//     string(21) "get_category_template"
//   }
//   [5]=>
//   array(3) {
//     ["type"]=>
//     string(4) "date"
//     ["condition"]=>
//     string(7) "is_date"
//     ["template"]=>
//     string(17) "get_date_template"
//   }
//   [6]=>
//   array(3) {
//     ["type"]=>
//     string(3) "day"
//     ["condition"]=>
//     string(6) "is_day"
//     ["template"]=>
//     string(17) "get_date_template"
//   }
//   [7]=>
//   array(3) {
//     ["type"]=>
//     string(5) "front"
//     ["condition"]=>
//     string(13) "is_front_page"
//     ["template"]=>
//     string(23) "get_front_page_template"
//   }
//   [8]=>
//   array(3) {
//     ["type"]=>
//     string(4) "home"
//     ["condition"]=>
//     string(7) "is_home"
//     ["template"]=>
//     string(17) "get_home_template"
//   }
//   [9]=>
//   array(3) {
//     ["type"]=>
//     string(5) "month"
//     ["condition"]=>
//     string(8) "is_month"
//     ["template"]=>
//     string(17) "get_date_template"
//   }
//   [10]=>
//   array(3) {
//     ["type"]=>
//     string(4) "page"
//     ["condition"]=>
//     string(7) "is_page"
//     ["template"]=>
//     string(17) "get_page_template"
//   }
//   [11]=>
//   array(3) {
//     ["type"]=>
//     string(5) "paged"
//     ["condition"]=>
//     string(8) "is_paged"
//     ["template"]=>
//     string(18) "get_paged_template"
//   }
//   [12]=>
//   array(3) {
//     ["type"]=>
//     string(15) "postTypeArchive"
//     ["condition"]=>
//     string(20) "is_post_type_archive"
//     ["template"]=>
//     string(30) "get_post_type_archive_template"
//   }
//   [13]=>
//   array(3) {
//     ["type"]=>
//     string(6) "search"
//     ["condition"]=>
//     string(9) "is_search"
//     ["template"]=>
//     string(19) "get_search_template"
//   }
//   [14]=>
//   array(3) {
//     ["type"]=>
//     string(6) "single"
//     ["condition"]=>
//     string(9) "is_single"
//     ["template"]=>
//     string(19) "get_single_template"
//   }
//   [15]=>
//   array(3) {
//     ["type"]=>
//     string(6) "sticky"
//     ["condition"]=>
//     string(9) "is_sticky"
//     ["template"]=>
//     string(19) "get_single_template"
//   }
//   [16]=>
//   array(3) {
//     ["type"]=>
//     string(8) "singular"
//     ["condition"]=>
//     string(11) "is_singular"
//     ["template"]=>
//     string(21) "get_singular_template"
//   }
//   [17]=>
//   array(3) {
//     ["type"]=>
//     string(3) "tag"
//     ["condition"]=>
//     string(6) "is_tag"
//     ["template"]=>
//     string(16) "get_tag_template"
//   }
//   [18]=>
//   array(3) {
//     ["type"]=>
//     string(3) "tax"
//     ["condition"]=>
//     string(6) "is_tax"
//     ["template"]=>
//     string(21) "get_taxonomy_template"
//   }
//   [19]=>
//   array(3) {
//     ["type"]=>
//     string(4) "time"
//     ["condition"]=>
//     string(7) "is_time"
//     ["template"]=>
//     string(17) "get_date_template"
//   }
//   [20]=>
//   array(3) {
//     ["type"]=>
//     string(4) "year"
//     ["condition"]=>
//     string(7) "is_year"
//     ["template"]=>
//     string(17) "get_date_template"
//   }
// }
```

Return Value
---
**array**
