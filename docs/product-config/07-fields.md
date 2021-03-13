# Fields

In this tab, you can add and configure module fields

<img srcset="./images/fields-table.jpg 2x" class="border padding">

Start by adding a new field then you can change its properties directly in the list

<img srcset="./images/field-example.jpg 2x" class="padding border">

### Name
The field name is only used in the backoffice and it's used to reference the field in the formulas.  
This name should be lower case and should only contain alphanumerical characters in addition to the underscore.  
Here are some examples:
- width
- height
- unit_price
- option1
- option2

### Label
This label will be displayed to the customers, it can be translated to all available languages

### Type
The module supports many field types, here's the full list 

---
##### Numeric Input
Displays a numeric field

<img srcset="./images/fields/numeric.jpg 2x" class="padding border">

You can access more settings by clicking the settings icon

<img srcset="./images/fields/numeric-settings.jpg 2x" class="border">

When both _min_ and _max_ are set to 0, the module will not validate them.

---
##### Slider
Displays a slider (from the jQueryUI library)

<img srcset="./images/fields/slider.jpg 2x" class="padding border">

The slider settings show these options

<img srcset="./images/fields/slider-settings.jpg 2x" class="border">

---
##### Dropdown

Displays a dropdown list (a HTML select)

<img srcset="./images/fields/dropdown.jpg 2x" class="padding border">

You can add dropdown options in the field settings

<img srcset="./images/fields/dropdown-settings.jpg 2x" class="border">

In most cases, the values and secondary values of the options are arbitrary.  
The field value will be the value of the selected option, so you can use the field directly in the formulas.

You can also assign a color or an image to each option if needed

<img srcset="./images/fields/dropdown-images-config.jpg 2x" class="border">

The module will then display the corresponding image or color when an image is selected

<img srcset="./images/fields/dropdown-image.jpg 2x" class="padding border">

---
##### Radio buttons

Display radio buttons

<img srcset="./images/fields/radio.jpg 2x" class="padding border">

You can add radio option in the field settings

<img srcset="./images/fields/radio-settings.jpg 2x" class="border">

---
##### Image list

Displays a list of images or colors

<img srcset="./images/fields/image-list.jpg 2x" class="padding border">

You can configure the options in the field settings

<img srcset="./images/fields/image-list-settings.jpg 2x" class="border">

You can allow multiselection, where the customer can pick more than one option
You can also display the label of each option by enabling the "Display label" option

<img srcset="./images/fields/image-list-labels.jpg 2x" class="padding border">

You can also change the height of the thumbnails in pixels

---
##### Checkbox

Display a checkbox

<img srcset="./images/fields/checkbox.jpg 2x" class="padding border">

You can configure the checkbox in the settings popup

<img srcset="./images/fields/checkbox-settings.jpg 2x" class="border">

The value of the checkbox if either 0 or 1, so you can use its value like an on/off switch to add a conditional cost.

---
##### Text

Displays a text field

<img srcset="./images/fields/text.jpg 2x" class="padding border">

You can configure the text field in the field settings

<img srcset="./images/fields/text-settings.jpg 2x" class="border">

The text length will not be validated if both _min_ and _max_ are set to 0

---
##### Text Area

Displays a text area

<img srcset="./images/fields/textarea.jpg 2x" class="padding border">

You can find more options in the field settings popup

<img srcset="./images/fields/textarea-settings.jpg 2x" class="border">

The text length will not be validated if both _min_ and _max_ are set to 0

---
##### Date

Display a date field

<img srcset="./images/fields/date.jpg 2x" class="padding border">

More settings are available in the field settings popup

<img srcset="./images/fields/date-settings.jpg 2x" class="padding border">

###### Initial value
The possible values for the initial value are:
- empty
- 0 (will set the date to the current date)
- +dd/-dd (will set the date to X days before or after the current date) 
For example, you can set the initial date to +7 to set it to one week in the future


###### Min / Max date
You can either set the min/max value to +dd or -dd or set them to a specific date following the format dd/mm/yyyy
Examples:
- Min date: -10 (Minimum of 10 days before the current date)
- Max date: +30 (A maximum of one month in the future)
- Min date: 15/05/2021

---
##### Image

---
##### File

---
##### Fixed Value

---
##### Price

---
##### Dynamic Variable

---
##### Feature

---
##### Divider

---
##### Color picker

---
##### Error message
