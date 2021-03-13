# Formulas

To make dynamic calculations, the module uses a formula system.

<img srcset="./images/formula.jpg 2x">

The concept is to reference the fields by name between brackets, so if the field has the name **width**,
then it can be referenced as **[width]**

The module will then replace the field references with their corresponding values

?> The module formulas use the same syntax as **Excel**

Adding a field to the formula is easy, you just need to click the field button to insert it.

Here are some formula example to get an idea about the syntax
<code class="formula">**[width]** * **[height]** / 10000 * 50</code>

<code class="formula">(**[width]** + **[height]**) * 2</code>

Many Excel functions can be used
<code class="formula">POW(**[width]**, 2)</code>

If statement for conditional calculation
<code class="formula">IF(**[width]** > 100, 10, 12)</code>

?> The keyboard shortct to save a formula is **Ctrl** + **Enter**

### Price formula
This formula is used to calculate the cost of the customization.  

?> The result of this formula will be added to the base price of the product

The module applies the taxes and the reductions to this result.  
The reductions that the module supports are:
- Product specific prices
- Group reductions
- Category reductions


### Weight formula
This formula is used to calculate the extra weight that the customization adds.  
The result of this formula affects the shipping cost.
To display the result of this formula, you can enable [the weight display option](product-config/06-settings.md?id=display-weight-to-customers).

### Quantity formula
This formula affects the quantity that is retracted from the stock when the order is validated.  
This is useful when you want to retract meters for example instead of units.  

Example:  
You have a field named length that you would like to use to retract the number of ordered meters.  
You can configure this formula:  
<code class="formula">**[length]**</code>

If you'd like to retract by meter squared for example
<code class="formula">**[width]** * **[length]**</code>
