# Lolita Framework - Front-end recomendations

> **Widget Interfaces** - HTML block which is using a set of variables

> **Templates** - it's just snippets for fast coding

### Usage

```html
<!-- widget_area -->
<div class="widget_area some_widget_area">
    <!-- lf_breadcrumbs -->
    <div class="widget lf_breadcrumbs __widget_modificator">
        <!-- Array of: { [name], [link] } -->
        <nav>
            <ul>
                <li class=""><a class="" href="#">Home</a></li>
                <li class=""><a class="" href="#">Gene Splicing</a></li>
                <li class=""><a class="" href="#">Cloning</a></li>
            </ul>
        </nav>
    </div>
    <!-- /lf_breadcrumbs -->
</div>
<!-- /widget_area -->
```

### Widget Interfaces

**Breadcrumbs**

```html
<!-- lf_breadcrumbs -->
<div class="widget lf_breadcrumbs __widget_modificator">
    <!-- Array of: { [name], [link] } -->
</div>
<!-- /lf_breadcrumbs -->
```

**Custom HTML**

```html
<!-- lf_custom_html -->
<div class="widget lf_custom_html __widget_modificator">
    <!-- { [custom_html] } -->
</div>
<!-- /lf_custom_html -->
```

**Logo**

```html
<!-- lf_logo -->
<div class="widget lf_logo __widget_modificator">
    <!-- { [image_scr], [link] } -->
</div>
<!-- /lf_logo -->
```

**Menu**

```html
<!-- lf_menu -->
<div class="widget __widget_modificator">
    <!-- [menu_name], Array of: { [label], [link], [user_class] } -->
    <nav class="menu-[menu_name]-container">
        <ul class="menu">
            <li class="menu-item"><a href="#">Menu Item 1</a></li>
        </ul>
    </nav>
</div>
<!-- /lf_menu -->
```

**Slider/Carousel**

```html
<!-- lf_slider -->
<div class="widget lf_slider __widget_modificator">
    <!-- Array of: { [image_src], [title], [sub_title], [link] } -->
</div>
<!-- /lf_slider -->
```

**Social Networks**

```html
<!-- lf_social_networks -->
<div class="widget lf_social_networks __widget_modificator">
    <!-- Array of: { [link], [icon_class] } -->
</div>
<!-- /lf_social_networks -->
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

**Search**

```html
<form role="search" method="get" class="lf_search_form" action="/">
    <label>
        <input type="search" class="lf_search_form__search_field" placeholder="" value="" name="s" autocomplete="off">
        <input type="submit" class="lf_search_form__form_submit" name="submit" value="">
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
<span class="lf_subscribe__success-message" style="display:none;">success</span>
<span class="lf_subscribe__error-message" style="display:none;">error</span>
<div class="lf_subscribe__container">
    <form class="" action="/" method="post" accept-charset="utf-8">
        <input type="email" name="" required="required" class="lf_subscribe__email" placeholder="">
        <input type="submit" name="" class="lf_subscribe__submit" value="Versturen">
    </form>
</div>
```

