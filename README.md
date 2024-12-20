# ✨ Full Stack Realtime Chat App ✨  

A powerful real-time chat application built with modern technologies to deliver seamless communication and an exceptional user experience.  

## 🚀 Features  

- **Authentication & Authorization**: Secure login and sign-up with JWT.  
- **Real-time Messaging**: Powered by Socket.io for instant chat functionality.  
- **Online User Status**: Displays live user presence in the app.  
- **Global State Management**: Managed with Zustand for a clean and efficient state handling.  
- **Profile Image Upload**: Cloudinary integration for uploading and managing profile images.  
- **Error Handling**: Robust error management on both the server and client sides.  

## 🌟 Tech Stack  

- **Frontend**: React.js, TailwindCSS, Daisy UI  
- **Backend**: Node.js, Express.js, MongoDB  
- **Real-time Communication**: Socket.io  
- **Global State**: Zustand  
- **Authentication**: JWT  
- **File Storage**: Cloudinary  




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