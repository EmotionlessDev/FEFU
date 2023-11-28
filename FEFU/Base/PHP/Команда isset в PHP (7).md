2023:11:16 01:07
Tags: #PHP 
__
## Пример
Пусть у нас есть следующая переменная:
```php
<?php 
$test = null; 
?>
```

```php
<?php 
$test = null; 
if ($test !== null) { 
echo '+++'; 
} else { 
echo '---'; 
} 
?>
```

```php
<?php 
$test = null;
if (isset($test)) { 
echo '+++'; 
} else { 
echo '---';
} 
?>
```
### Zero-links

### Links
-