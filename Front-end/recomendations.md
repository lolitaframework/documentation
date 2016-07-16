# Lolita Framework - HTML Helpers

> **Widget Interfaces** - HTML block which is using a set of variables

> **Templates** - it's just snippets for fast coding

### Widget Interfaces

**Breadcrumbs**

```html
<!-- lf_interface_breadcrumbs -->
<div class="widget lf_interface_breadcrumbs">
    <!-- Array of: { $name, $link } -->
</div>
<!-- /lf_interface_breadcrumbs -->
```

**Custom HTML**

```html
<!-- lf_interface_custom_html -->
<div class="widget lf_interface_custom_html">
    <!-- { (custom_html) } -->
</div>
<!-- /lf_interface_custom_html -->
```

**Logo**

```html
<!-- lf_interface_logo -->
<div class="widget lf_interface_logo">
    <!-- { (image_scr), (link) } -->
</div>
<!-- /lf_interface_logo -->
```

**Menu**

```html
<!-- lf_interface_menu -->
<div class="widget lf_interface_menu">
    <!-- Array of: { (label), (link), (user_class) } -->
</div>
<!-- /lf_interface_menu -->
```

**Slider/Carousel**

```html
<!-- lf_interface_slider_style1 -->
<div class="widget lf_interface_slider_style1">
    <!-- Array of: { (image_src), (title), (sub_title), (link) } -->
</div>
<!-- /lf_interface_slider_style1 -->
```

**Social Networks**

```html
<!-- lf_interface_social_networks -->
<div class="widget lf_interface_social_networks">
    <!-- Array of: { (link), (icon_class) } -->
</div>
<!-- /lf_interface_social_networks -->
```

### Templates

**Article**

```html
<article>
    <header class="entry-header">
        <div class="entry-meta">
            <!-- entry meta -->
        </div>
    </header>
    <div class="entry-content">
        <!-- entry content -->
    </div>
    <footer class="entry-footer">
        <!-- entry  -->
    </footer>
</article>
```

**Breadcrumbs**

```html
<nav>
    <ul>
        <li class=""><a class="" href="#">Home</a></li>
        <li class=""><a class="" href="#">Gene Splicing</a></li>
        <li class=""><a class="" href="#">Cloning</a></li>
    </ul>
</nav>
```

**Logo**

```html
<a href="#" style="background-image:url('');"></a>
```

**Menu**

```html
<nav class="menu-menu_name-container">
    <ul class="menu">
        <li class="menu-item"><a href="#">Menu Item 1</a></li>
    </ul>
</nav>
```

**Search**

```html
<form role="search" method="get" class="search-form" action="/">
    <label>
        <input type="search" class="search-field" placeholder="" value="" name="s" autocomplete="off">
        <input type="submit" name="submit" value="">
    </label>
</form>
```

**Slider/Carousel**

```html
<ul class="">
    <li class="" style="background-image: url('');">
        <span class="">Logo</span>
    </li>
</ul>
```

**Social Networks**

```html
<ul>
    <li>
        <a href="#"><i class=""></i></a>
    </li>
</ul>
```

**Subscribe**

```html
<span class="lf_subscribe_style1__success-message" style="display:none;">success</span>
<span class="lf_subscribe_style1__error-message" style="display:none;">error</span>
<div class="lf_subscribe_style1__container">
    <form class="" action="/" method="post" accept-charset="utf-8">
        <input type="email" name="" required="required" class="" placeholder="">
        <input type="submit" name="" value="Versturen">
    </form>
</div>
```

