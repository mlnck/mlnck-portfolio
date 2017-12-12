---
title: My New Page
---
# My New Page!

This is the body of **my new page** and I can easily use _Markdown_ syntax here.

[https://learn.getgrav.org/basics/grav-configuration](https://learn.getgrav.org/basics/grav-configuration)

Use default, arbitrary config file(s) here. e.g. _data.yaml_ `conf` key can be seen:
```javascript
//twig template
{{ config.data.count }}
```
```php
//php
$count_var = Grav::instance()['config']->get('data.count');
```
