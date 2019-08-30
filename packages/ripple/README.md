# Svelte Material UI - Ripple

Ripples are an interaction feedback mechanism.

See [MDC Ripple](https://material.io/develop/web/components/ripples/) for more information on API and Sass mixins.

See [the Sass variable file](https://github.com/material-components/material-components-web/blob/v3.1.1/packages/mdc-ripple/_variables.scss) for styling variables.

# Installation

```sh
npm install --save-dev @svelte-material-ui/ripple
```

# Basic Usage

```html
<script>
  import Ripple from '@svelte-material-ui/ripple';
</script>

<p use:Ripple={[true, {color: 'surface'}]} tabindex="0">
  Here is an element with a ripple.
</p>
```

# Demo

*in action:* https://sveltematerialui.com/#/demo/ripple

*demo code:* https://github.com/hperrin/svelte-material-ui/blob/master/site/demos/Ripple.svelte

# Exports

## (default)

A ripple Svelte action.

### Props / Defaults

The action accepts an array, with two entries. The first is a boolean, whether the ripple is enabled. The second is an object with the props:

* `unbounded` - Whether the ripple is unbounded.
* `color` - The ripple color. ('surface', 'primary', or 'secondary')