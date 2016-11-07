
# `<raml-summary-view>`
A basic information about the RAML definition viewer for the documentation panel.

### Example
```
<raml-summary-view raml="[[raml]]"></raml-summary-view>
```
or in vanila JavaScript
```
let summary = document.querySelector('#raml-summary-view');
summary.raml = raml;
```

### Styling
`<raml-summary-view>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--raml-summary-view` | Mixin applied to the element | `{}`
`--raml-summary-view-title` | Mixin applied to the API title element | `{}`
`--raml-summary-view-property` | Mixin applied to each line of attributes applied in the basic documentation view | `{}`
`--raml-summary-view-description-color` | Color of the description of the API. | `rgba(0, 0, 0, 0.54)`

