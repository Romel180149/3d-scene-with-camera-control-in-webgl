# Interactive 3D WebGL Scene with Camera Control

This project is a 3D scene created using **Three.js** with interactive controls and dynamic object rotation. The user can rotate and move the camera around the scene, and there is an interactive GUI to control object animations and lighting effects.

### Features:
- **Camera Control**: Move and rotate the camera using mouse controls (OrbitControls).
- **Interactive GUI**: Use the `dat.GUI` panel to adjust the rotation speed of objects and toggle shadows and animations.
- **Dynamic Lighting**: The scene is illuminated by ambient, directional, and point lights to enhance the realism.
- **Shadows**: Toggle shadows on and off for objects in the scene.

### Demo

You can try the live demo of the 3D scene [here](https://3d-moving-webgl.netlify.app/).

### How to Use:
1. **Rotate the Cube and Sphere**: Use the `dat.GUI` controls to change the rotation speed of the cube and sphere.
2. **Camera Controls**: Click and drag the mouse to orbit the camera around the scene.
3. **Resize**: The scene is responsive and adjusts its size based on the window size.

### Technologies Used:
- **[Three.js](https://threejs.org/)**: A JavaScript library for 3D rendering in the browser.
- **[dat.GUI](https://github.com/dataarts/dat.gui)**: A lightweight controller library for creating interactive user interfaces.
- **WebGL**: A powerful API for rendering 3D graphics within the browser.

### Installation Instructions:
To run this project locally, follow these steps:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/3d-scene-with-camera-control-in-webgl.git
