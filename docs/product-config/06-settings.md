In this tab, you can find the general product settings.  
<img srcset="./images/module-interface.jpg 2x" class="border">

---
#### Enable the module for this product
If enabled, the fields will be displayed on the current product page
<img srcset="./images/enable-option.jpg 2x" class="border">

---
#### Required customization
When enabled, an error will be displayed if the customization is not completely filled

---
#### Displayed price
If you set the product base to 0, you can use this option to display a price in the category page.  
<img srcset="./images/display-price-config.jpg 2x" class="border">

The price will be displayed like this  
<img srcset="./images/display-price.jpg 2x">

?> The module applies the configured tax to the displayed price

##### Price unit
If filled, the price unit will be displayed like this  
<img srcset="./images/price-unit.jpg 2x">

##### Display the calculated price
You can also display the calculated price which will be calculated based on the initial values of your fields

---
#### Display weight to customers
When enabled, the result of the weight formula will be displayed  
<img srcset="./images/display-weight.jpg 2x" class="border padding">

---
#### Hide quantity input
When enabled , the module will hide the PrestaShop quantity field  
If the input is not hidden correctly, you can hide it using custom css
```css
/* Example */
body.dp-hide-qty .product-quantity {
  display: none !important;
}
```

---
#### Multiply price & weight by quantity
If activated, the displayed price & weight on the product page will be multiplied by the quantity


---
#### Copying configurations
You can copy a configuration from one product to another or from a product to a category

##### Load configuration
You can copy a product configuration to the current product by picking a product from the list  

<img srcset="./images/load-config.jpg 2x" class="border padding">

!> The configuration of the current product will be overwritten

##### Copy configuration
You can copy the current product configuration to any category of your choice. 

<img srcset="./images/copy-config.jpg 2x" class="border padding">

!> The configuration of all the products of the selected category will be overwritten

##### Import / Export configuration
You can also import / export the configuration as a file or copy / paste it from clipboard

<img srcset="./images/import-export.jpg 2x" class="border padding">
