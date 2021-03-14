# Custom scripts

You can use custom scripts to customize the module behaviour.  
You can create javascript files in these folders:

- `/js/dynamic` (create the `dynamic` folder if it doesn't exist)
- `/themes/[current theme]/assets/js/dynamic`

The file name should be:

- `custom.js` (if you want to target all products)
- `customX.js` (if you want to only target the product with ID=**X**)  
  For example, if you want to target product `#10`, you can create a file named `custom10.js`

### Detecting a field change

To detect a field change, you can create a function with the same name as the field but prefixed with `dp_`.  
For example, if you have a field named `width`, you can create a function named `dp_width`.  
Code example:

```js
function dp_width(value) {
  // The current value of the field
  console.log(value);
}
```

If you have a field which has options, the selected options will also be passed to the custom function

```js
function dp_dropdown(value, selected_options) {
  // selected_options is an array containing the IDs of the selected options
  console.log(value, selected_options);
}
```

### Updating the properties of a field

You can change a field properties from the custom script, for that you need to use the `updateField` function.  
Code example:

```js

updateField(field_name, props);

// This example will change the value of the width field as well as the min, max and step
updateField("width", {
  value: 50,
  min: 10,
  max: 100,
  step: 10
});
```

The props object can have these items

```ts
// The props interface has this shape
export interface IFieldSettings {
  value: string | number;
  min: number;
  max: number;
  step: number;
  required: number;
  max_size: number;
  min_date: string;
  max_date: string;
  multiselect: boolean;
  display_value_price: number;
  display_secondary_value_price: number;
  display_in_popup: number;
}
```
