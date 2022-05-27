# PostTypeHandler
Class helpers to handle fast PostType and Taxonomies declarations

## Usage
Below is a basic example of setting up a simple PostType.

```php
// don't forget to import your autoloader
require_once __DIR__ . '/vendor/autoload.php';

use PostTypeHandler\PostType;

$post_type_handler = new PostType( 'Book' );
$post_type_handler->register();
```

## TODOS
- Add filters to custom the params of the post type
- Add filters to custom the labels of the post type