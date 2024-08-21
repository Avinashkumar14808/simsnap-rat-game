SimSnap - Cross-Device Interactive Platform

Overview

SimSnap is a cross-device interactive platform developed as part of a research project during the Mitacs Globalink Research Internship in Canada. The project aims to enhance user experiences in gaming and learning applications by combining dynamic cross-device interaction with spatial rearrangement. The platform enables multiple devices, such as Chromebooks, to connect and work together interactively, creating a unified and adaptable game environment.

Problem Statement

With the widespread use of mobile devices, there is a significant opportunity to develop collaborative systems that leverage multiple devices. However, existing systems often focus on either creating complex device arrangements with simple interactions or facilitating complex interactions without considering device arrangement. SimSnap addresses this gap by combining both aspects—dynamic interaction across multiple devices and the ability to rearrange devices spatially.

Features

Snapping and Unsnapping
Devices can be connected (snapped) to form a larger display or disconnected (unsnapped) to create a dynamic and adaptable game environment.

Game Mechanics
SimSnap includes a simple yet engaging "rat game" where the player controls a rat that can move up, down, left, or right across connected devices. The rat seamlessly transitions from one device's screen to another. Obstacles block the rat's path, adding a challenge, while encountering fruits can lead to gaining points or progressing to the next level.

Technical Implementation

Frontend: Developed using React.js to manage the user interface and handle device interactions.
Backend: Implemented with Express.js to manage server communication and device connectivity.
Real-Time Communication: WebSocket is used to synchronize the game state across multiple devices, ensuring smooth and real-time interaction.
Challenges and Solutions

Device Synchronization: Ensuring smooth and synced movement of the rat across all connected devices was achieved using WebSocket for real-time communication.
Dynamic Interaction: Snapping and unsnapping devices seamlessly required dynamically adjusting the game grid and reconfiguring the display area, allowing the game environment to adapt instantly as devices were added or removed.
Learning and Impact

This project provided hands-on experience in cross-device interaction, multi-device communication, and user experience design. It also offered insights into human-computer interaction and the challenges of developing collaborative, multi-device systems.

Conclusion

SimSnap successfully demonstrates the potential of collaborative, multi-device systems through a functional and engaging cross-device game. This project was a rewarding experience, allowing for the application of technical skills in a real-world research setting while contributing to broader research goals.

Getting Started

To run this project locally, follow these steps:

cd simsnap
Install dependencies:

npm install
Start the development server:

npm start
Connect multiple devices: Ensure all devices are on the same network and access the game through the provided URL.
License

This project is licensed under the MIT License - see the LICENSE file for details.


