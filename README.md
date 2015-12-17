# `FormField`

## Decendants

* `FormField-label`
* `FormField-input` (text-like inputs)
* `FormField-inputPrefix`
* `FormField-inputSuffix`
* `FormField-radio`
* `FormField-radio`
* `FormField-dropdown`
* `FormField-option` name?
* `FormField-optionLabel` name?
* `FormField-message` (should this just be FormField-error)

## Modifiers

* `FormField--stacked` (stacked by default, but this will apply margins)
* `FormField--inline`
* `FormField--floatLabel`
* `FormField-message--error`

## States

* `.is-error`
* `.is-disabled`

```html
<div class="FormField FormField--floatLabel">
  <input class="FormField-input" type="text">
  <label class="FormField-label">My Floating Label</label>
</div>

<div class="FormField">
  <h2 class="FormField-label">Some heading for a checkbox, if desired.</h2>
  <div class="FormField-option">
    <input class="FormField-checkbox" type="checkbox">
    <label class="FormField-optionLabel">Single Checkbox...Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vehicula faucibus leo id pellentesque. Proin eu malesuada massa. Vivamus commodo rhoncus luctus. Morbi at nibh nisl, sed hendrerit augue.</label>
  </div>
</div>

<div class="FormField">
  <h2 class="FormField-label">Group Label</h2>
  <div class="FormField-options">
    <div class="FormField-option">
      <input class="FormField-radio" type="radio">
      <label class="FormField-optionLabel">Radio 1</label>
    </div>
    <div class="FormField-option">
      <input class="FormField-radio" type="radio">
      <label class="FormField-optionLabel">Radio 2</label>
    </div>
  </div>
</div>
```
