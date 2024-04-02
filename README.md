## Live video chat Project

## Overview
This project aims to provide a WebRTC-based solution for video calling and adding members to ongoing calls. It utilizes WebRTC technology to establish peer-to-peer connections between clients for real-time communication. Additionally, it offers the functionality to dynamically add members to ongoing video calls, enabling collaborative experiences.

## Features
- **Video Calling**: Users can initiate video calls with other participants in real-time.
- **Peer-to-Peer Communication**: Utilizes WebRTC for establishing direct connections between clients, ensuring low-latency and high-quality video communication.
- **Member Addition**: Allows for the dynamic addition of members to ongoing video calls, enabling collaborative sessions.
- **Responsive Interface**: The interface is designed to be responsive across various devices and screen sizes.

## Usage
1. **Setup**: Clone the repository and install necessary dependencies.
2. **Configuration**: Configure the application settings such as signaling server URL, authentication mechanism (if applicable), etc.
3. **Run**: Start the application server.
4. **Initiate Video Call**: Navigate to the video calling interface, enter the necessary details (room name, participant names, etc.), and start the call.
5. **Add Members**: During an ongoing call, use the designated functionality to add members by specifying their details.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/webrtc-project.git
   ```

2. Install dependencies:
   ```bash
   cd web-task2
   npm install
   ```

3. Configure the application by modifying the configuration files as necessary.

4. Run the application:
   ```bash
   for server - npm start
   for frontend - cd frontend and then npm run start
   ```
## Dependencies
- **WebRTC**: Utilized for real-time peer-to-peer communication.
- **Node.js**: Runtime environment for server-side code.
- **Express.js**: Framework for building web applications in Node.js.
- **Socket.io**: Enables real-time, bidirectional, and event-based communication.

## Contributing
Contributions are welcome! Feel free to open issues or pull requests with suggestions, bug fixes, or new features.

