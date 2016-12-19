# react-mdl-css

Use Custom style from https://getmdl.io/customize in your react-mdl app, you don't have to use the default style provided by [react-mdl](https://github.com/react-mdl/react-mdl).

> :information_source: This Package won't work without [react-mdl](https://github.com/react-mdl/react-mdl), so make sure to include it.

# Quick-Start Guide

- [Installation](#installation)
- [Development Workflow](#development-workflow)

## Installation

**1. Install the package:**

```sh
npm install -save react-mdl-css
```

## Development Workflow

**2. Include the customized style from getmdl.io in your index.html:**

```html
<!-- A basic example with purple primary color and pink accent color -->
<link rel="stylesheet" href="https://code.getmdl.io/1.2.1/material.purple-pink.min.css" />
```

**3. Include react-mdl & react-mdl-css in your entry file (index.js):**

```js
import 'react-mdl-css/material.css';
import 'react-mdl/extra/material';
```

> :information_source: We're done here. You don't need to import `react-mdl/extra/material.css`

## License

MIT
