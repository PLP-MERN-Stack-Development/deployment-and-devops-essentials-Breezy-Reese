# TODO: Integrate MongoDB to Store Sent Messages

- [x] Install mongoose dependency
- [x] Create Message model/schema in models/Message.js
- [x] Update server.js to connect to MongoDB using provided URI
- [x] Modify 'send_message' socket event to save messages to DB
- [x] Update 'send_file' socket event to save file messages to DB
- [x] Update 'private_message' socket event to save private messages to DB
- [x] Update 'react_to_message' socket event to update reactions in DB
- [x] Update 'message_read' socket event to update read status in DB
- [x] Update /api/messages route to fetch from DB with pagination
- [x] Test the integration

# TODO: Update URLs for Hosted Environment

- [x] Create server/.env with CLIENT_URL=https://week-7-mern-rust.vercel.app/
- [x] Create client/.env with VITE_SOCKET_URL=https://deployment-and-devops-essentials-breezy.onrender.com
