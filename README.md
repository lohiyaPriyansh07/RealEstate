# Real Estate Project

A full-stack real estate web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js), styled with Tailwind CSS, and using Firebase for Google Authentication.

## Deployment

You can find the live deployment of this project [here](https://bluesky-estate-hub.onrender.com).

## Features

- User Authentication with Google using Firebase
- Listing of properties with details
- Add, Edit, Delete property listings
- User profile management
- Responsive design with Tailwind CSS

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Tailwind CSS
- Firebase Authentication

## Installation

### Backend

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/blog-website.git
    cd blog-website/backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the `backend` directory and add your MongoDB URI and JWT secret:
    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:
    ```sh
    npm run start / node index.js
    ```

### Frontend

1. Navigate to the frontend directory:
    ```sh
    cd ../client
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the React development server:
    ```sh
    npm start dev
    ```


## Project Structure

```plaintext
real-estate-project/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   └── propertyController.js
│   ├── models/
│   │   ├── User.js
│   │   └── Property.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── propertyRoutes.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── .env
│   ├── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── tailwind.css
│   ├── .env
│   ├── package.json
│   ├── tailwind.config.js
├── README.md
```


