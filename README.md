# Sahii Blog App

This repository contains the code for the Sahii Blog App, which consists of both the front-end and back-end components. The application allows users to read articles, manage posts, and perform various administrative tasks related to the blog.

## Frontend

The frontend of the Sahii Blog App is built using React.js and styled using TailwindCSS to ensure responsiveness across all devices. Here's a breakdown of the key features and components developed for the frontend:

- **Articles Page**: Displays a list of articles using React Router Dom for navigation.
- **Footer**: Provides essential links and information at the bottom of each page.
- **CTA Section**: Presents a call-to-action section to encourage user engagement.
- **Article Card Component**: Represents individual articles in a visually appealing card format.
- **Hero Section**: Engages users with a captivating hero section at the top of the page.
- **Responsive Header**: Ensures the header remains user-friendly across different devices.
- **Pagination**: Implements pagination functionality for navigating through articles efficiently.
- **Search Between Posts**: Allows users to search for specific articles.
- **Loading & Error State for Posts**: Enhances user experience by providing feedback during loading and error states.
- **Profile Page**: Enables users to view and update their profiles, including uploading profile pictures.
- **Authentication**: Implements user authentication functionalities like login, logout, and registration.
- **Redux Integration**: Utilizes Redux for state management, ensuring a smooth and consistent user experience.
- **Social Media Sharing**: Allows users to share articles on various social media platforms.
- **Comment Management System**: Provides administrators with tools to manage comments efficiently.
- **TipTap Editor**: Implements a rich text editor for creating and editing blog content.
- **Responsive Design**: Ensures the application is responsive and accessible across different devices and screen sizes.

## Backend

The backend of the Sahii Blog App is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. Here's an overview of the key features and functionalities developed for the backend:

- **Dependencies Installation**: Before running the backend, make sure to download the dependencies by navigating to the backend directory and running `npm install`.
- **MongoDB Setup**: Create a MongoDB database to store the application's data. You can use a cloud-based MongoDB service like MongoDB Atlas or set up a local MongoDB instance.
- **Environment Variables**: Create a `.env` file in the backend directory and set the following environment variables:
  - `DB_URI`: MongoDB connection URI.
  - `PORT`: Port number for the backend server.
  - `JWT_SECRET`: Secret key for JSON Web Token (JWT) authentication.
  - `NODE_ENV`: Environment mode (`development`, `production`, etc.).
- **Run the Backend**: Once the dependencies are installed and environment variables are configured, run the backend server using `yarn dev` command.

## Installation

To run the Sahii Blog App locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Mo-Gamer-2000/Sahii.git`
2. Navigate to the backend directory: `cd backend_blog_app`
3. Install dependencies: `npm install`
4. Create a MongoDB database and obtain the connection URI.
5. Create a `.env` file in the backend directory and set the following environment variables:
6. Run the backend server: `yarn dev`
7. Navigate to the frontend directory: `cd frontend_blog_app`
8. Install frontend dependencies: `npm install`
9. Start the frontend server: `npm start`
10. Open your browser and visit `http://localhost:3000` to view the application.

## Contributing

Contributions to the Sahii Blog App are welcome! If you'd like to contribute, please follow these guidelines:

- Fork the repository and create a new branch for your feature or bug fix.
- Ensure your code adheres to the project's coding conventions and style guidelines.
- Write clear and concise commit messages.
- Test your changes thoroughly.
- Submit a pull request detailing the changes you've made and any relevant information.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Contact

For questions or inquiries about the Sahii Blog App, please contact [Moeez Abdul](https://www.linkedin.com/in/moeezabdul/).
