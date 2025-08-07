# Job Portal (jobportal-yt)

A full‑stack job portal web application built with the MERN stack (MongoDB, Express, React, Node.js). Recruiters can post jobs and review candidates; applicants can browse and apply to jobs with resumes and SOPs.

## 🚀 Features

### 🔸 Two user roles
- **Job Applicant**: register/login, browse/search/filter jobs, upload resume/SOP, apply to jobs.
- **Recruiter**: register/login, post new jobs, view applicants per job, shortlist & accept or reject candidates.

### 🔧 Dashboard functionality
- Applicants see the jobs they’ve applied for and application status.
- Recruiters see all posted jobs and management tools for applicants.

### ✨ Additional Features (optional)
- File uploads (resume/SOP, profile image)
- Search, sort & filter job listings
- Email notifications for candidate status updates
- Role-based access control

## 🧰 Technology Stack

- **Frontend**: React.js, Redux (if used), React Router, Axios, styled-components (or CSS/Bootstrap)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ORM)
- **Authentication**: JSON Web Tokens (JWT), bcrypt for password hashing


## 🔧 Installation & Running Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/samipevekar/Job-Portal-Task.git
   cd Job-Portal-Task

2. Backend
  ```bash
cd backend
npm install
node index.js
```
3. Frontend
  ```bash
cd frontend
npm install
npm run dev
```

## Env setup (backend)
```bash
PORT = 9803
SECRET_KEY = secret_key
CLOUD_NAME = ksldjfklsj
API_KEY = 19820938092203
API_SECRET = sdjklfskskl
MONGO_URI = mongodb://sldkfj:slkdfj/JobPortal
```


