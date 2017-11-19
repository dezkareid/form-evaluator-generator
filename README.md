# \<form-evaluator-generator\>

`<form-evaluator-generator>` is a compo.

```html
<form-evaluator-generator fields='[{ "label" : "Name", "name": "name", "pattern" : "[a-zA-Z]*", "error" : "El nombre tiene caracteres desconocidos", "attributes" : [ { "disabled" : false }] }]'>
       </form-evaluator-generator>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--form-evaluator-button-theme`| Mixin applied to the button's style | `{}` |
| `--form-evaluator-button-hover` | Mixin applied to the button's style when hover event happens | `{}` |
| `--form-input-container-label` | Mixin applied to the form's container labels | `{}` |
| `--form-input-container-label-floating` | Mixin applied to the form's labels container when the label is floating | `{}` |
| `--form-input-container-input` | Mixin applied to the form's container input | `{}` |
| `--form-input-container-input-focus` | Mixin applied to the form's inputs when the input is in focus | `{}` |
| `--form-input-container-input-invalid` | Mixin applied to the form's inputs when the input is no valid | `{}` |
| `--form-dropdown-menu` | Mixin applied to the form's dropdowns | `{}` |
| `--form-dropdown-menu-button` | Mixin applied to the form's dropdowns buttons | `{}` |
| `--form-dropdown-menu-input` | Mixin applied to the form's dropdowns inputs | `{}` |
| `--form-dropdown-menu-icon` | Mixin applied to the form's dropdowns icons | `{}` |
| `--paper-checkbox-label` | Mixin applied to the form's checkbox label | `{}` |
| `--form-checkbox-label-checked` | Mixin applied to the form's checkbox when is checked| `{}` |
| `--form-listbox` | Mixin applied to the form's listbox | `{}` |


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
