2023:11:16 01:14
Tags: #PHP
__
## Пример
```php
<?php 
if (isset($arr['test'])) { 
$elem = $arr['test']; 
} else { 
$elem = 'empty'; 
} 
// or
$elem = isset($arr['test']) ? $arr['test'] : 'empty';
// or
$elem = $arr['test'] ?? 'empty';
?>
```
### Zero-links

### Links
-