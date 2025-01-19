#  Full Stack Realtime Chat App 
The project is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) combined with Socket.io for real-time capabilities, TailwindCSS for styling, and Daisy UI for an enhanced design system.It features robust authentication and authorization implemented using JSON Web Tokens (JWT). Real-time messaging functionality is powered by Socket.io, allowing seamless communication between users, along with an online user status indicator to show active participants. The application leverages Zustand for efficient global state management, ensuring a smooth user experience. Comprehensive error handling has been implemented both on the server and client sides to provide a reliable and user-friendly platform.


### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
