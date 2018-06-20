# ractive-select2-component
A simple component that uses select2 library to render dropdowns. Use option and bind it to an array of objects and objects should have two keys atleast the option value should be in the key id and the option display should be in the key text.

To get the value of selected option you can bind to returnSelected.

Example:

```html
<select2 option="{{other}}" returnSelected="{{otherSelectedItems}}"/>
```
When a dropdown item is selected on the above select2 component ```JavaScript ractive.get('otherSelectedItems')``` will give you the result of selected dropdown item.
