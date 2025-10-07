# Video-Conferencing-and-Collaboration-Platform (MERN + WebRTC Stack).
1. This is a Video Conferencing and Collaboration Platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) combined with WebRTC for real-time communication.
2. It enables video conferencing, screen sharing, and text chat — providing a seamless virtual meeting experience.

# Features 🚀
🎥 Real-Time Video Calls – Connect multiple users via live peer-to-peer video sessions using WebRTC.

💬 Instant Messaging – Send and receive messages within the meeting room in real-time.

🖥 Screen Sharing – Share your screen instantly with other participants.

🎧 Audio / Video Controls – Easily mute, unmute, or disable the camera while in a session.

➕ Room Management – Create and join rooms using unique meeting IDs.

⚡ Socket.io Signaling Server – Enables efficient peer connection establishment.

📱 Responsive Interface – Optimized for both desktop and mobile browsers.

🔐 Optional Authentication – Add login and room-level access control (if integrated).


# Tech Stack 🛠️

Frontend: React.js, Tailwind CSS, WebRTC, Socket.io-client

Backend: Node.js, Express.js, Socket.io

Database: MongoDB (Mongoose ODM)

Real-Time Communication: WebRTC (STUN/TURN + PeerConnection)

☁️ Environment Config – Uses .env variables for server setup and API key management.

🚀 Full-Stack Integration – RESTful backend with real-time signalling for smooth user experience.

# This is Basic overlook of the project :

1. Home page is the following :
   <img width="1917" height="1007" alt="Screenshot 2025-10-07 225429" src="https://github.com/user-attachments/assets/c53183b1-293a-4d84-9a46-b071937f704b" />
2. Sign/Login Page :
   <img width="1919" height="1006" alt="Screenshot 2025-10-07 225458" src="https://github.com/user-attachments/assets/150b46a1-a39d-4daf-9406-e34290e9eac6" />
3. Creating Meeting Code :
   <img width="1919" height="1001" alt="Screenshot 2025-10-07 225510" src="https://github.com/user-attachments/assets/f50e0857-4fec-405d-b404-665b1cd1d1b2" />
4. Entering into the Lobby(Camera Access Authentication) : 
   <img width="1919" height="999" alt="Screenshot 2025-10-07 225531" src="https://github.com/user-attachments/assets/6f36fa03-004b-459a-b28a-f4f4734cb9c2" />
5. Entering into the Lobby(Voice Access Authentication) :
   <img width="1919" height="1008" alt="Screenshot 2025-10-07 225540" src="https://github.com/user-attachments/assets/03c540d4-217e-4f66-be43-d4af382d32ac" />
6. Main Video Call Page(Along with Chating Feature) :
   <img width="1919" height="1008" alt="Screenshot 2025-10-07 225704" src="https://github.com/user-attachments/assets/acee36e8-13d1-4658-a5eb-ad84cd79332a" />
7. Screen Sharing Feature :
   <img width="1919" height="1001" alt="Screenshot 2025-10-07 225713" src="https://github.com/user-attachments/assets/244457f7-316a-4d65-80b0-ccba7e27aa03" />
8.Lastly the History Page :
   <img width="1919" height="1005" alt="Screenshot 2025-10-07 225734" src="https://github.com/user-attachments/assets/8c667d74-fedf-4c98-a1a4-efc32602c8fa" />


# Getting Started ⚡
Setup Instructions : 
Clone the Repository : git clone https://github.com/jayant200803/Video-Conferencing-and-Collaboration-Platform.git
cd Video-Conferencing-and-Collaboration-Platform
Install Dependencies
For both frontend and backend:

cd client
npm install
cd ../server
npm install


Set Up Environment Variables
Create a .env file inside the server folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
NODE_ENV=development


(If using STUN/TURN servers)

STUN_SERVER_URL=your_stun_server_url
TURN_SERVER_URL=your_turn_server_url
TURN_SERVER_USERNAME=your_turn_username
TURN_SERVER_CREDENTIAL=your_turn_credential


Run the Application

# Run backend
cd server
npm start

# Run frontend
cd client
npm start

# Future Enhancements 💡
🎞 Multi-User Grid View – Display multiple participants dynamically in a grid layout.

📁 Meeting Recording – Add support to record video/audio sessions.

🔐 User Authentication – Add login and role-based access (Host / Participant).

💾 Persistent Chat Storage – Save in-call messages for future reference.

🌐 Deployment – Host the app on Render, Vercel, or Railway, with MongoDB Atlas.

📱 Improved Mobile Layout – Optimize for smartphones and tablets.






