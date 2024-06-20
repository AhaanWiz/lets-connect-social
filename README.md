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
