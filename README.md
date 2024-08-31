# E-commerce Application

This is a MERN stack-based e-commerce application with the backend deployed on Vercel and the frontend handled separately.
Here You can Find The Frontend Repo ( https://github.com/arpitkasaudhan/E-commerce-Using-MERN-Stack )

## Features

- **Product Catalog**: Browse, filter, and sort product listings.
- **User Authentication**: Secure login and registration functionality.
- **Shopping Cart**: Add, update, and persist items in the cart.
- **Order Processing**: Place orders with payment gateway integration (Stripe).
- **Product Images**: Upload and manage product images.
- **Reviews and Ratings**: Submit and view product reviews and ratings.
- **Promotional Discounts**: Apply discount codes and promotions.
- **User Profile Management**: Update and manage user information.
- **Order History**: View past orders and track shipment status.
- **Admin Panel**: Manage products, users, and orders.

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have the following installed on your system:

- Node.js (v14 or later)
- npm (v6 or later)

### Frontend Setup

1. **Clone the Frontend Repository**:
    ```bash
    git clone https://github.com/arpitkasaudhan/E-commerce-Using-MERN-Stack.git
    cd E-commerce-Using-MERN-Stack
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Start the Frontend**:
    ```bash
    npm run start
    ```
 - The server is running on http://localhost:3000`

4. **Deploy to Backend Repository**:
    - After building, copy the contents of the `build` folder and place them in the backend repository's public directory.

### Backend Setup

1. **Clone the Backend Repository**:
    - Replace `your-backend-repo-link` with your backend GitHub repository link.
    ```bash
    git clone yhttps://github.com/arpitkasaudhan/fgecom
    cd backend-repo-directory
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Configure Environment Variables**:
    - Create a `.env` file in the root directory and add the necessary environment variables:

    ```
    MONGO_URI=your_mongo_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the Application**:
    ```bash
    npm run dev
    ```

    - The server should be running on `http://localhost:5000`.

### Accessing the Application

- Once both frontend and backend are set up, visit `http://localhost:5000` to access the application.

## Deployment

The application is deployed on Vercel. You can access it via the deployed link:
[Deployed Application](https://your-vercel-app-link)


