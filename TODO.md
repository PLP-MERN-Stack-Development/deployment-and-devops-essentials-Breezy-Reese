# TODO: Connect to MongoDB Database and Integrate Message Persistence

- [x] Update server/package.json to add mongoose dependency
- [x] Edit server/.env to add MONGO_URI
- [x] Modify server/server.js to add MongoDB connection logic
- [x] Run npm install in server directory
- [x] Test the server connection (run npm run dev and check logs)
- [x] Import Message model in server.js
- [x] Update send_message handler to save messages to MongoDB
- [x] Update send_file handler to save file messages to MongoDB
- [x] Update /api/messages endpoint to fetch from MongoDB
