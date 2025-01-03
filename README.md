# CMY Cube Visualization

A 3D visualization of a CMY cube built using [Three.js](https://threejs.org/). This project demonstrates rendering a cube with transparent materials representing the CMY (Cyan, Magenta, Yellow) color model.

## Preview

<a href="https://makalin.github.io/CMY-Cube/cmy-cube.html" target="_blank">Live Preview</a>

## Features

- **Three.js**: Leveraging the power of Three.js for 3D rendering.
- **Custom Materials**: Transparent materials to showcase CMY colors.
- **Dynamic Lighting**: Ambient and directional lights for realistic shadows and reflections.
- **Orbit Controls**: Easy rotation, zooming, and panning of the camera.
- **Responsive Design**: Automatically adjusts to window resizing.

## Installation

Clone the repository and open the `cmy-cube.html` file in a modern browser.

```bash
git clone https://github.com/your-username/cmy-cube-visualization.git
cd cmy-cube-visualization
```

## Usage

1. Open the `cmy-cube.html` file in your preferred browser.
2. Use your mouse to rotate, zoom, and pan the camera around the cube.

## Code Structure

### Scene Setup

- **Scene**: The 3D environment.
- **Camera**: A perspective camera with field of view set to 75 degrees.
- **Renderer**: WebGL renderer with shadow mapping enabled.

### Cube

- A cube with six sides, each painted with a transparent CMY color material.
- **Materials**:
  - Cyan
  - Magenta
  - Yellow

### Lighting

- **Ambient Light**: Provides base illumination.
- **Directional Lights**: Simulates sunlight from different angles.

### Controls

- `OrbitControls`: Enables smooth camera interactions.

## Dependencies

- [Three.js](https://threejs.org/) (via CDN)
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) (via CDN)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Made with ❤️ using [Three.js](https://threejs.org/).
