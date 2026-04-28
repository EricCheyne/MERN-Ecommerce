# MERN Ecommerce

## Full Stack E-Commerce Store App

A modern online store built with the MERN stack, featuring product browsing, cart management, user authentication, and order checkout.

## Tech Stack
- MongoDB
- Express
- React
- Node.js

## Features
- Product listing and detail pages
- Shopping cart and checkout flow
- User registration and login
- Admin product management
- Secure backend APIs with authentication

## Getting Started

### Prerequisites
- Node.js (16+)
- npm or yarn
- MongoDB Atlas or local MongoDB instance

### Installation

1. Clone the repository
   ```bash
   git clone <repo-url>
   cd MERN-Ecommerce
   ```
2. Install dependencies
   ```bash
   npm install
   ```

### Environment Variables
Create a `.env` file in the backend folder (or root if the app is configured that way) with values such as:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
CLIENT_URL=http://localhost:3000
```

### Run the App

Start the development server:

```bash
npm run dev
```

Or start production-style builds:

```bash
npm start
```

## Project Structure

A typical MERN e-commerce app is organized like this:

- `backend/` - Express API, database models, routes, controllers
- `frontend/` - React client, pages, components, state management
- `config/` - environment and database configuration
- `models/` - MongoDB schemas
- `routes/` - API route definitions
- `controllers/` - request handling logic

## Notes

- Replace placeholder environment values before running.
- Ensure MongoDB is available and the connection string is valid.
- If using separate front-end and back-end packages, run install and start commands in each folder.

## License

This project is available under the MIT License.
