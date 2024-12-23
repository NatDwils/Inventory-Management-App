# Inventory Management App

The **Inventory Management App** is a robust and user-friendly MERN (MongoDB, Express.js, React.js, Node.js) application designed for efficient inventory management. The app includes features such as:

- **Data Validation**: Using Joi for ensuring accurate data input.
- **Email Verification**: For secure password resets.
- **Cloudinary Integration**: For seamless product image uploads.

## Features

- Add, update, view, and delete inventory items.
- Secure authentication with email verification.
- Intuitive user interface for managing inventory.
- Responsive design for desktop and mobile devices.

---

## Installation

Follow these steps to install and run the Inventory Management App:

### Prerequisites

Ensure you have the following installed:

- **Node.js**: [Download Node.js](https://nodejs.org/)
- **MongoDB**: [Install MongoDB](https://www.mongodb.com/try/download/community)
- **Git**: [Download Git](https://git-scm.com/)

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/NatDwils/Inventory-Management-App.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd inventory-management-app
   ```

3. **Install Dependencies**:

   ```bash
   npm install
   ```

4. **Set Up Environment Variables**:
   
   Create a `.env` file in the root directory and add the following variables:
   
   ```env
   PORT=5000
   MONGO_URI=<Your MongoDB connection string>
   CLOUDINARY_NAME=<Your Cloudinary cloud name>
   CLOUDINARY_API_KEY=<Your Cloudinary API key>
   CLOUDINARY_API_SECRET=<Your Cloudinary API secret>
   JWT_SECRET=<Your JWT secret key>
   ```

---

## Usage

1. **Start the Application**:

   ```bash
   npm start
   ```

2. **Access the Application**:
   
   Open a web browser and navigate to [http://localhost:3000](http://localhost:3000).

3. **Perform Actions**:
   
   - **Log In or Sign Up**: Create an account or log in to access the dashboard.
   - **Manage Inventory**: Add, update, or delete inventory items.
   - **Image Uploads**: Upload profile picture using Cloudinary integration.

---

## Technologies Used

The Inventory Management App leverages the following technologies:

- **Frontend**:
  - React.js
  - Tailwind CSS (for styling)

- **Backend**:
  - Node.js
  - Express.js

- **Database**:
  - MongoDB (NoSQL database)

- **Cloud Services**:
  - Cloudinary (for image storage)

---

## API Endpoints

### Authentication

- **POST /api/users/register**: Register a new user.
- **POST /api/users/login**: Log in a user.
- **POST /api/users/resetPassword**: Request a password reset.

### User Profile 

- **GET /api/users/profile**: Retrieve User Profile.
- **POST /api/users/updateProfile**: Update User Profile.
- **PUT /api/users/updateProfilePicture**: Update User Profile Picture.

### Inventory Management

- **GET /api/inventory**: Retrieve all inventory items.
- **POST /api/inventory**: Add a new inventory item.
- **PUT /api/inventory/:id**: Update an inventory item.
- **DELETE /api/inventory/:id**: Delete an inventory item.

---

## Contact

For questions or support, please contact:
- **Email**: [ishikanimade56@gmail.com](mailto:ishikanimade56@gmail.com)

