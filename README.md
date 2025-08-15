## SDATDevOps Final Sprint – Frontend

### Overview
This repository contains the frontend for the SDATDevOps Final Sprint project.  
It is a React application that communicates with the backend API to provide user-facing functionality.

---
### Prerequisites
- Node.js 16+
- npm or yarn
- Access to the backend API (running locally or deployed)

---

### Getting Started (Local Development)

#### 1. Clone the repositories
```bash
git clone https://github.com/<your-username>/SDATDevOps-FinalSprint_backend.git
git clone https://github.com/<your-username>/SDATDevOps-FinalSprint_frontend.git
```

#### 2. Install dependencies
```bash
npm install
```

#### 3. Configure environment variables
Create a `.env` file in the frontend repo:
```env
REACT_APP_API_URL=http://localhost:8080
```

#### 4. Start the frontend
```bash
npm start
```
Frontend runs at [http://localhost:3000](http://localhost:3000).

---

### Deployment Notes
- Ensure `REACT_APP_API_URL` points to the deployed backend API.
- Build the frontend for production:
```bash
npm run build
```
- Deploy the `build/` directory to your hosting provider.

---

## Author:
###  --- Harini Manohar --- :)
### SD-12 | Semester-4 | Final Sprint for SDAT & DevOps
### Date: Aug 15, 2025
