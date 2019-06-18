## aframe-camera-transform-controls-component

[![Version](http://img.shields.io/npm/v/aframe-camera-transform-controls-component.svg?style=flat-square)](https://npmjs.org/package/aframe-camera-transform-controls-component)
[![License](http://img.shields.io/npm/l/aframe-camera-transform-controls-component.svg?style=flat-square)](https://npmjs.org/package/aframe-camera-transform-controls-component)

A Camera Transform Controls component for [A-Frame](https://aframe.io).

### API

| Property    | Description                                               | Default Value |
| ----------- | --------------------------------------------------------- | ------------- |
| enabled     |                                                           | `true`        |
| cameraRigId | Camera rig containing the camera and both controllers     | `cameraRig`   |
| onStart     | Event used to start the panning or scale & rotate         | `gripdown`    |
| onEnd       | Event used to stop panning or scale & rotate              | `gripup`      |
| showHint    | Show a line between both controllers and the scale factor | `true`        |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-camera-transform-controls-component/dist/aframe-camera-transform-controls-component.min.js"></script>
</head>

<body>
  <a-scene camera-transform-controls=""> </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-camera-transform-controls-component
```

Then require and use.

```js
require('aframe');
require('aframe-camera-transform-controls-component');
```
