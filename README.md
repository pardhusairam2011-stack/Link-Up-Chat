🚀 Overview

LinkUp Chat is a fully browser-based, peer-to-peer (P2P) messaging application that allows two users to communicate in real time using a simple room code. It is built using HTML, CSS, and JavaScript, and uses WebRTC (via PeerJS) to create a direct connection between users without needing a backend server.

Unlike traditional chat apps, messages are sent directly between devices, making communication faster, more private, and server-free.

⚙️ How It Works

LinkUp Chat uses a room code system to connect users. When one user creates a room, a unique code is generated. The second user enters this code to join.

Behind the scenes, PeerJS handles the connection setup while WebRTC creates a direct browser-to-browser link. Once connected, messages travel directly between users without passing through a server.

💬 Features

Room code system (no login required)
Real-time messaging using WebRTC
Direct peer-to-peer communication
Clean chat bubble interface
Light/Dark mode toggle
Press Enter to send messages
Responsive design for different devices
Auto-scroll to latest messages

🧑‍💻 How to Use
🟢 Creating a Room

Open the HTML file in your browser
Click Create Room
A room code will be generated
Share this code with your friend

🔵 Joining a Room

Open the same file in another browser or device
Enter the room code
Click Join
Wait a few seconds for connection

💬 Sending Messages

Type your message in the input box
Press Enter or click Send
Your messages appear on the right
Friend’s messages appear on the left

🌗 Switching Theme

Click the moon icon in the header
Switch between light and dark mode
Your preference is saved automatically

🎨 User Interface Design

The UI is modern and minimal with a clean layout. The header contains the app name and theme toggle. Below it is the control section for creating or joining rooms, followed by the chat area where messages are displayed.

Messages are aligned clearly, with your messages on the right and the other user’s messages on the left, creating a familiar chat experience similar to popular messaging apps.

🧠 Technical Highlights

Uses WebRTC for real-time communication
Uses PeerJS for simplified connection setup
DOM manipulation for updating chat dynamically
Event handling for user interactions
localStorage for saving theme preference
Organized and modular JavaScript structure

🌍 Advantages

No backend server required
Fast communication through direct connection
Better privacy since messages are not stored
Easy to run by simply opening the HTML file

⚠️ Limitations

Requires internet for initial connection
Best suited for two users
Connection quality depends on network

🌟 Conclusion

LinkUp Chat is a strong demonstration of modern web development using real-time communication without traditional servers. It combines functionality, performance, and clean UI design into a single project.

It serves as an excellent portfolio project, showcasing advanced concepts like peer-to-peer networking, real-time data transfer, and interactive user interface design.
