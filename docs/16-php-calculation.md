# PHP Calculation

If your calculation is very complex or requires custom logic, then you can use a PHP file to do it.
PHP can help you in these situations for example:
- Your calculation is too complex to be written in a formula
- You want to access a PrestaShop variable that is not available in the formula
- You want to fetch data from a remote service

Here are the available methods to use a PHP file:
- To calculate the [price formula](product-config/08-formulas.md?id=price-formula)
- To calculate the [weight formula](product-config/08-formulas.md?id=weight-formula)
- To calculate the [quantity formula](product-config/08-formulas.md?id=quantity-formula)
- To assign the value of a [dynamic field](product-config/07-fields.md?id=dynamic-variable) from PHP
- To declare JavaScript variable to use it in a custom script

### Accessing fields from PHP
In any PHP file that you create inside the folder `/dynamicproduct/`, the fields will be available
with their current values.
For example, if you have fields `width`, `length` and `height`, you can access them using the variables
`$width`, `$length` and `$height` respectively.  
In the same way, you can change a field value by directly assigning a new value to the corresponding
variable, for example:
```php
$width = 10;
$length = 15;
$text = 'Hello';
```

### Price calculation using PHP
To calculate the price, place a PHP file in the folder `/dynamicproduct/calculator`
- Name the file `products.php` if you want to target all products
- Name the file `productX.php` if you want to target only the product with ID=X  
  For example:  
    `product1.php` will target product `#1`  
    `product42.php` will target product `#42`  
  The product **ID** is displayed in the product list in the backoffice  
  <img srcset="./images/php-ids.jpg 2x" class="padding border">
