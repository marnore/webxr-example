# WebXR example

This is the code sample of WebXR and three.js integration. Wroks on Android ARCore [supported devices](https://developers.google.com/ar/discover/supported-devices) with Chrome 81+

Running instructions:

1. Download [three.js srouce code](https://github.com/mrdoob/three.js/releases/tag/r120) and place it under `three.js` subdirectory. 
OR if you don't want to download the full source code:
    
    * Download [GLTFLoader.js](https://github.com/mrdoob/three.js/blob/r120/examples/jsm/loaders/GLTFLoader.js) and place it under `three.js/examples/jsm/loaders/`
    * Download [three.module.js](https://github.com/mrdoob/three.js/blob/r120/build/three.module.js) and place it under `three.js/build/`

2. Install `npm`

3. Generate self-signed certificates `openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

4. Initialize project `npm init -y && npm install node-static`

5. Start the server `npm start`

6. Make sure your smartphone is connected to the same network as your PC, open Chrome and navigate to [https://your_local_ip:3000/webxr-threejs.html](https://your_local_ip:3000/webxr-threejs.html)
