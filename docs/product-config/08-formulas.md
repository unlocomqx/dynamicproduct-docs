# Formulas

To make dynamic calculations, the module uses a formula system.

<img srcset="./images/formula.jpg 2x">

The concept is to reference the fields by name between brackets, so if the field has the name **width**,
then it can be referenced as **[width]**

The module will then replace the field references with their corresponding values

?> The module formulas use the same syntax as **Excel**

Adding a field to the formula is easy, you just need to click the field button to insert it.

Here are some formula example to get an idea about the syntax
<code class="formula lang-text">**[width]** * **[height]** / 10000 * 50</code>

<code class="formula lang-text">(**[width]** + **[height]**) * 2</code>

Many Excel functions can be used
<code class="formula lang-text">POW(**[width]**, 2)</code>

If statement for conditional calculation
<code class="formula lang-text">IF(**[width]** > 100, 10, 12)</code>
