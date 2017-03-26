## aframe-slice9-component

A Slice9 component for A-Frame.

For [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
| width       |             | 1              |
| height      |             | 1              |
| left        |             | 0              |
| right       |             | 0              |
| bottom      |             | 0              |
| top         |             | 0              |
| side        |             | front              |
| padding     |             | 0.1              |
| color       |             | #fff              |
| opacity     |             | 1.0              |
| transparent |             | true              |
| debug       |             | false              |
| map         |             | ''              |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.4.0/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-slice9-component/dist/aframe-slice9-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity slice9="foo: bar"></a-entity>
  </a-scene>
</body>
```

<!-- If component is accepted to the Registry, uncomment this. -->
<!--
Or with [angle](https://npmjs.com/package/angle/), you can install the proper
version of the component straight into your HTML file, respective to your
version of A-Frame:

```sh
angle install aframe-slice9-component
```
-->

#### npm

Install via npm:

```bash
npm install aframe-slice9-component
```

Then require and use.

```js
require('aframe');
require('aframe-slice9-component');
```
