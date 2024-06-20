# Let's Connect Social

Welcome to the Let's Connect Social project! This guide will help you set up the project locally.

## Prerequisites

- Git
- Node.js
- npm

## Steps to Set Up the Project Locally

1. **Clone the Repository**

   Use the following git command to clone the project repository:

   ```sh
   git clone https://github.com/AhaanWiz/lets-connect-social.git
2. **Navigate to the Project Directory**

   ```sh
   cd lets-connect-social
3. **Set Environment Variables**

   Create a .env file in the root directory and set the following environment variables:

   ```env
   PORT=your_port_number
   MONGO_URI=your_mongo_uri
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret

4. **Install Dependencies and Build the Project**

   Run the following command to install all the dependencies for both the server and the backend, and to prepare the project for production:

   ```sh
   npm run build

5. **Start the Project**

   Finally, start your project with the following command:

   ```sh
   npm start

## Technologies Used

- **MongoDB**: A widely-used NoSQL database for efficient data storage and retrieval.
  
- **ExpressJS**: A minimalist web framework for Node.js that simplifies building robust APIs and web applications.
  
- **React**: A powerful JavaScript library for building user interfaces with a component-based architecture and efficient rendering.
  
- **NodeJS**: An asynchronous event-driven JavaScript runtime environment, designed to build scalable network applications.
  
- **Recoil**: A state management library for React applications, offering a more intuitive and flexible approach to managing state.
  
- **JWT (JSON Web Tokens)**: A compact, URL-safe means of representing claims securely between two parties, commonly used for user authentication and authorization.
  
- **BCryptJS**: A JavaScript library for hashing passwords using bcrypt, ensuring secure storage of user credentials.
  
- **Cloudinary**: A cloud-based service that provides an end-to-end image and video management solution, including storage, manipulation, optimization, and delivery.
  
- **Socket.io**: A library that enables real-time, bidirectional, and event-based communication between clients and servers using WebSockets, essential for building applications that require instant data updates.
  
- **ChakraUI**: A simple, modular component library for React applications that helps in creating accessible and responsive user interfaces with ease.
  
- **React-icons**: A library that provides a collection of free, high-quality icons to use in React applications, enhancing visual appeal and functionality.

# Features

- Using JWT token for secure registration and login which will generate a token with a 14-day expiry. This token will be used for authenticating and providing current user data to our backend.

- Full CRUD (Create, Read, Update, Delete) functionality to create and edit user profiles, allowing users to manage their personal information and preferences.

- Complete CRUD functionality with a RESTful API for users to post various types of content, including text, images, videos, and links, enabling rich and diverse user interactions.

- Built with Express to provide functionality for interacting with other users' posts, including liking, commenting, and sharing, to foster community engagement.

- Implemented real-time messaging between users using Socket.io, allowing for instant communication and enhancing user connectivity.

- Storing a comprehensive database that includes posts, users, messages, likes, comments, and other relevant data to ensure robust data management and retrieval.

- Webapp can be viewed in both dark mode and light mode, with the help of ChakraUI, offering users a customizable and visually appealing interface.

