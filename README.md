##&lt;paper-accordion&gt;

`paper-accordion` is a material design styled Polymer 1.0 component for the accordion [pure javascript, no libraries].

[Live Example](http://spacee.xyz/polymer-components/paper-accordion/demo.html)

##Installing with Bower

To install the component with the Bower, just run:

`bower install --save paper.accordion`

Example:

```html
<link href="path/to/paper-accordion/paper-accordion.html" rel="import">

...

<paper-accordion>
    <paper-accordion-item title="Addy Osmani" icon="add" icon-position="left" sub-title="@polymer">
        The first.
    </paper-accordion-item>
    <paper-accordion-item title="Rob Dodson" icon="add" icon-position="left" sub-title="@polymer">
        The second.
    </paper-accordion-item>
    <paper-accordion-item title="Paul Irish" icon="add" icon-position="left" sub-title="@chrome">
        The third.
    </paper-accordion-item>
    <paper-accordion-item title="Rouben Meschian" icon="add" icon-position="left" sub-title="@cambridesemantics">
        The fourth.
    </paper-accordion-item>
</paper-accordion>
```

### Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--paper-accordion-item-header-background` | The background color of the accordion header | `transparent` |
| `--paper-accordion-item-header-border-color` | The border color of the accordion header container | `rgba(0, 0, 0, 0.25)` |
| `--paper-accordion-item-header-color` | The text color of the accordion header container | `black` |
| `--paper-accordion-item-header-icon-color` | The icon color of the accordion header container | `black` |
| `--paper-accordion-item-content-background` | The accordion content background color | `rgba(0,0,0,0.1)` |
| `--paper-accordion-item-content-color` | The accordion content text color | `black` |

###&lt;paper-accordion&gt; - Properties

The following properties are available:

| Property Name | Description | Default |
| --- | --- | --- |
| `close-others` | If it's 'true' there could me only one opened accordion | `false` |

###&lt;paper-accordion-item&gt; - Properties

The following properties are available:

| Property Name | Description | Default |
| --- | --- | --- |
| `icon` | The name of the icon | `icons:chevron-right` |
| `icon-position` | The position of the icon (left || right) | `left` |
| `title` | The title of the accordion item header | `` |
| `sub-title` | The sub title of the accordion item header | `` |
