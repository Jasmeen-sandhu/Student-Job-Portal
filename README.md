# CareerBridge — BCA Student Job Application Portal

A full-stack, GitHub-ready job portal designed for BCA students and fresh graduates.

## Features
- Student and employer registration/login with JWT cookie sessions
- Job search and job-type filtering
- Employer job posting and deletion
- Student applications with PDF/DOC/DOCX resume upload
- Student application tracking dashboard
- Employer candidate dashboard with status updates
- Admin account support
- SQLite database (no separate database server required)
- Responsive modern UI

## Demo accounts
- Student: `student@demo.com` / `password123`
- Employer: `employer@demo.com` / `password123`
- Admin: `admin@demo.com` / `password123`

## Run locally
1. Install Node.js 18+.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.

The database file `jobportal.db` and uploaded resumes are created automatically.

## Production notes
Set `JWT_SECRET` to a long random value. For production, use HTTPS and move uploads/database to managed storage/services.
