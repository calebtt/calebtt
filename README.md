# 👋 Hi, I’m @calebtt

- 🌱 Currently diving into *Multi-paradigm Design in C++*
- 📫 Best way to reach me: email preferred. Cell available by request for faster back-and-forth. NashDev slack for Nashville local.

---

### 🚧 Projects in Progress

1. arc_client

The arc_client is a Windows desktop application designed for appremotecontrol.com. Developed in C++17, it leverages Boost libraries like Asio and Beast for SSL-secured WebSocket communications. The client facilitates remote control functionalities by simulating input devices, allowing users to manage their systems remotely. The project utilizes VCPKG for dependency management, ensuring streamlined integration of necessary libraries.

2. arc_server

Complementing the desktop client, a C++17 intermediate server is under development to handle secure WebSocket connections between clients and controllers. This server manages communication between web client (Web Interface) and desktop client (arc_client). It's built using Boost.Beast and OpenSSL for performant and secure data transmission.​

3. Web Interface

A responsive web interface is also in progress, providing users with an intuitive platform to interact with their devices remotely. The interface includes directional controls and buttons for mouse actions, facilitating comprehensive remote management. Built with modern web technologies, it ensures compatibility across various devices and browsers.​

4. Android App

Play Store app, Kotlin + Android Studio. More featured with a better user xp web interface.

These projects collectively aim to deliver a cohesive remote control solution, integrating desktop applications, secure servers, and user-friendly web interfaces.

You can check on the progress and test the system live by visiting https://appremotecontrol.com/

Notes:
1. I am in the process of moving the intermediate server (arc_server) that relays commands to either self hosting or a cheaper VPS, it may be unavailable for a while.

---

### 💻 AI powered VoIP PBX Based Tech Project Launching Soon
Expect a mix of:
- C# .NET SIP client deployed to VPS handling large call volume
- Javascript and HTML front-ends
- Telephone network connectivity (PSTN), callable via cell or landline phone
- Public SIP code: https://github.com/calebtt/SipBotLib

More details (and code) coming soon.

Notes:
1. PSTN Number to dial is 1-615-899-3270
2. The VAD (Voice Activity Detection), NS (Noise Suppression), and AEC (Acoustic Echo Cancellation) isn't (yet) perfect and is causing some ghost transcriptions if you have it on speaker with background noise.
3. Availability depends on whether or not it's running on my desktop rig at the moment.

---

### 📺 Favorite CppCon Talks  
Here’s a shortlist of the C++ talks I come back to most:  
📄 https://pastebin.com/FysxbMQ0

> *If I’d started using GitHub earlier, there’d be a lot more stuff here.*  
> That said, expect more code, tools, and ideas to show up soon.

---

<!---
calebtt/calebtt is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
