php_apk_parser
==============

Android APK XML File Decompress Class For PHP

#Example

```php
<?php
require('apk_parser.php');
$p = new ApkParser();
$res = $p->open('android_app.apk');
echo $p->getXML();
?>
```