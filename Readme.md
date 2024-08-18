# Twitube

Twitube is a backend-focused project that combines features from popular platforms like Twitter and YouTube. This repository contains the backend implementation, designed to handle various aspects of user management, content creation, media storage, and more.

## Features

- **User Authentication**: Secure user registration and login using JWT (JSON Web Tokens) and bcrypt for password hashing.
- **Content Management**: Endpoints for users to create, edit, delete, and interact with text posts (tweets) and video content.
- **Media Storage**: Integration with Cloudinary for seamless media storage and retrieval, handling both images and videos.
- **Database Management**: Efficient data storage and retrieval using MongoDB, with Mongoose as the ODM (Object Data Modeling) library.
- **API Design**: RESTful API design with clear and consistent endpoints for various operations.
- **Error Handling**: Comprehensive error handling and validation to ensure a smooth user experience.
- **Scalability**: Designed with scalability in mind, allowing the application to handle increasing user load and data volume.

-[Models URL](https://app.eraser.io/workspace/cyjBFpxitYH8RsEJCHoA)
-[UI](https://www.figma.com/design/VYQHKdaN6qTfhowlnVFHZU/PLAY-(Copy)?node-id=0-1&t=mLA6Xx3Eap4CmWgQ-0)

## Technologies Used

- **Node.js**: The core runtime for building the backend.
- **Express.js**: The web application framework used to structure the API.
- **MongoDB**: A NoSQL database used for storing user data, posts, and media references.
- **Mongoose**: An ODM for MongoDB, providing a schema-based solution for data modeling.
- **JWT**: For user authentication and session management.
- **Bcrypt**: For securely hashing user passwords.
- **Cloudinary**: For managing media uploads and storage.
- **Other Tools**: Various middleware and utilities to enhance the functionality and security of the backend.

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone http://github.com/devankitmishra/twitube.git
   ```
2. **Install dependencies:**
   ```bash
   cd twitube
   npm install
   ```
3. **Set up environment variables:** Create a .env in root of project and fill in the required values in the .env file using .env.sample file

4. **Start the server:** 
   ```bash
   npm run dev
   ```
   
## Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes. Make sure to follow the existing coding standards and write tests for any new features.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software. See the [LICENSE](LICENSE) file for more details.
