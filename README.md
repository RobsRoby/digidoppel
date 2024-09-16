<img src="https://github.com/RobsRoby/digidoppel/blob/main/icon-text.png" alt="PomoPets Logo" width="100">

# DigiDoppel
DigiDoppel is a JavaScript application that leverages TensorFlow and Three.js to create a live 3D avatar of your face. By utilizing face mesh technology, DigiDoppel allows you to generate a dynamic and interactive digital clone of yourself in real-time.

## Features
- **Live Face Mesh**: Uses TensorFlow's face mesh technology to track facial features and movements in real time.
- **3D Avatar**: Creates a 3D model of your face using Three.js, providing a live avatar experience.
- **Real-Time Interaction**: Your avatar updates in real-time as you move and change expressions.
- **Local or Web Server Support**: Can be hosted on a local server or deployed on the web for easy access.

## Prerequisites
To run DigiDoppel, you'll need the following:
- A local or web server (e.g., Node.js, XAMPP, or any other HTTP server)
- A web browser that supports WebGL
- Internet connection (for TensorFlow.js and Three.js dependencies)

## Getting Started

### 1. Set Up the Server
To run DigiDoppel, you must have a local or web server. Here’s how to set up a local server using a few common methods:

#### Using Node.js
1. Install [Node.js](https://nodejs.org/).
2. Navigate to the project directory in your terminal.
3. Run the following command to install a simple HTTP server:
   ```bash
   npm install -g http-server
   ```
4. Start the server:
   ```bash
   http-server
   ```
5. Open your web browser and go to `http://localhost:8080` (or the port number provided).

#### Using XAMPP
1. Install [XAMPP](https://www.apachefriends.org/index.html).
2. Place the DigiDoppel project folder inside the `htdocs` directory of your XAMPP installation.
3. Start the Apache module in XAMPP.
4. Open your web browser and go to `http://localhost/DigiDoppel`.

### 2. Run the Application
1. Once the server is running, open the project URL in your web browser.
2. Allow the browser to access your webcam when prompted.
3. The application will use TensorFlow.js to track your face and Three.js to generate a live 3D avatar.

## Usage
- The app will start capturing your facial features in real time.
- Your live avatar will reflect your facial movements, providing an interactive 3D model of your face.

## Dependencies
DigiDoppel relies on the following libraries:
- [TensorFlow.js](https://www.tensorflow.org/js): For face mesh tracking
- [Three.js](https://threejs.org/): For rendering the 3D model
- WebGL: Ensure your browser supports WebGL for 3D rendering.

## Contributing
Contributions are welcome! If you'd like to contribute to DigiDoppel, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Support
If you encounter any issues or have questions, please contact the project maintainers or refer to the documentation provided in the project files.
