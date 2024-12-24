# Job Listing App

A simple, yet powerful job listing app where job seekers can browse and apply for jobs. This application is designed to streamline the hiring process, providing a user-friendly platform for job seekers.

## Features

- **Employer Features**:
  - Post job openings with descriptions, requirements, and other details.
  - View applicants who have applied to their jobs.
  
- **Job Seeker Features**:
  - Browse job listings by category, location, and other filters.
  - View detailed job descriptions and apply directly to jobs.


## Tech Stack

- **Frontend**: Next.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: Render (for backend), Netlify (for frontend)

## Installation

To run the app locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/job-listing-app.git
cd job-listing-app
```

### 2. Set up the Backend

- Go to the `backend` directory:
  
```bash
cd backend
```

- Install Dependencies:
 ```bash
  npm install
 ```

- Create a .env file and add the required environment variables:
```bash
touch .env
```

- Add env variables:
```bash
MONGO_URI=your-mongo-database-url
PORT=5001
```

- Start the Server
```bash
npm run dev
```
### 3. Setup Frontend

- Go to the `frontend` directory:
```bash
cd frontend
```

- Install Dependencies:
 ```bash
  npm install
 ```

- Create a .env file and environment variable:
```bash
touch .env
```

- Add env variables:
```bash
NEXT_PUBLIC_APP_URL=http://localhost:5001
```
- Start the frontend
```bash
npm run dev
```
