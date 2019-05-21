# XML sitemap - Plugin for IO CMS

```php
$sitemap = new PHPXMLSitemap('https://example.com');
$sitemap->add('/', '1.0', 'daily', '2019-03-20');
$sitemap->add('about');
$sitemap->render();
```

## Libraries used

- https://github.com/jenstornell/php-xml-sitemap