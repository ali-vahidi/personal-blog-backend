# Personal Blog – Backend

This repository contains the **backend part** of a full-stack **MERN** project built with **Node.js**, **Express.js**, and **MongoDB**.

I was responsible for the backend – including routing, models, controllers, and server setup.

## Project Structure

```
mern-blog/
├── backend/
├── client/
├── dashboard/
```

## Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)
- MongoDB (running locally)


## Setup Instructions

1. Navigate to the project root:
   ```bash
   cd personal-blog-backend
   ```
2. Create a `config.env` file and add the following:
   ```env
   DATA_BASE=mongodb://localhost:27017/Blog-Vahidi
   PORT=5000
   JWT_SECRET=Vahidi
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the server:
   ```bash
   npm run dev
   ```

## Environment Variables

```env
DATA_BASE=mongodb://localhost:27017/Blog-Vahidi
PORT=5000
JWT_SECRET=Vahidi
```

## Available Scripts

```bash
npm run dev  # Starts the backend server in development mode.
```

## Notes

1. Replace `http://localhost:5005/api/` and `http://localhost:5005/` with the correct URLs if your backend is running on a different port.  
2. Ensure MongoDB is running locally or update the `DATA_BASE` variable with your remote MongoDB connection string.  
3. Adjust the `PORT` in the backend `.env` file if needed.
