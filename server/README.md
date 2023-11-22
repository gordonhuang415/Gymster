# Gymster 

### **Description**

Gymster is a full stack, responsive social media app that uses the MERN stack (MongoDB, ExpressJS, React, Node). Gymster consists of a register page with complete validation along with functionality to upload a user profile image. After registration, a login page is used for user login to enter the home page. The home page consists of a user widget that displays user information, a post functionality that allows users to create posts with images and descriptions, a friend list widget that displays the user's friends list, and a news feed that shows posts from the user, other users, and friends of the user. Each post has a like and comment functionality that tracks the number of likes one each post and allows users to like posts; users are also able to make and view comments on each post. From each post, a user can add a friend and the friend list widget will update with the added friend. Friends can also be removed from the friend list. From each post, the user is able to navigate to the profile of that user and see their posts along with their friend list. The navigation bar includes the feature to change the app from normal mode to dark mode. The app will also adjust to smaller screens when used on mobile.

#### Frontend:
- React - Frontend framework
- React Router - Used for navigation 
- Formik and Yup - Form and form validation  
- Redux Toolkit - Used for state management 
- Redux with persist - Used to store in local storage
- React Dropzone - Allows for image uploads

#### Backend:
- Node.js - Runtime
- Express.js - Backend Framework
- Mongoose - Manage Mongo database
- JWT (Json Web Token) - Authentication 
- Multer - For file upload 
