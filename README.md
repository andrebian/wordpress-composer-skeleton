#Esqueleto Wordpress com Composer


Ver http://www.andrebian.com/wordpress-e-composer-parte-2/

###Constantes no wp-config

```php
// ... após a constante de debug

define( 'WP_CONTENT_DIR', dirname(__FILE__) . '/wp-content' );
define( 'WP_CONTENT_URL', 'http://localhost/nome-do-projeto/wp-content' );
```