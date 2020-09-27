# WebXR example

This is the code sample of WebXR and three.js integration. Wroks on Android ARCore [supported devices](https://developers.google.com/ar/discover/supported-devices) with Chrome 81+

Running instructions:

Download [three.js srouce code](https://github.com/mrdoob/three.js/releases/tag/r120) and place it under `three.js` subdirectory

Install `npm`

Generate self-signed certificates `openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

Initialize project `npm init -y && npm install node-static`

Start the server `npm start`
