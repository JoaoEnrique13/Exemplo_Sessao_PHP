# criando_sessao.php
```php
<?php
session_start();

$_SESSION["newsession"]=$value;

?>
```

# capturando_sessao.php
```php
<?php
session_start();

$_SESSION["newsession"]=$value;

echo $_SESSION["newsession"];
?>
```

# atualizando_sessao.php
```php
<?php
session_start();

$_SESSION["newsession"]=$value;

$_SESSION["newsession"]=$updatedvalue;
?>
```

# excluindo_sessao.php
```php
<?php
session_start();

$_SESSION["newsession"]=$value;
unset($_SESSION["newsession"]);

?>
```
