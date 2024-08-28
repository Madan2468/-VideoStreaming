

## Video Upload & Playback Platform (Proof of Concept)

This project is a platform that allows users to upload and watch videos. The backend is fully functional, built with **Node.js** and **Express.js**, utilizing **Multer** for file uploads and **ffmpeg** for video processing. The frontend is developed using **React**.

### Technologies Used:
- Node.js: Backend runtime environment
- Express.js: Web framework for Node.js
- React: Frontend JavaScript library
- Multer: Middleware for handling file uploads
- ffmpeg: Tool for video processing
- Postman: API testing tool

 Key Features:
- Video Uploads: Users can upload videos seamlessly through the backend.
- Video Playback: Uploaded videos can be watched on the frontend.
- Postman: Used for comprehensive testing of backend API endpoints.

 Current Status:
The backend is fully operational, and the frontend is complete but has not been deployed due to the need for paid subscriptions. As a result, this project currently serves as a proof of concept.

 How to Test:
- Testing: Use Postman to test the backend. After uploading a video, the generated video link will be provided.
- Viewing the Video**: To watch the uploaded video, manually add the generated link to `const videoLink` in `app.js` on the frontend.

