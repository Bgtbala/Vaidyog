🩺 Vaidyog – Healthcare Job Portal

A healthcare-focused job platform built using the MERN stack, designed to streamline recruiter-candidate interactions with secure role-based authentication, data-driven insights, and optimized search performance.

🚀 Tech Stack

Frontend: React.js, Chart.js, Redux / Context API
Backend: Node.js, Express.js
Database: MongoDB (Aggregation Framework)
Deployment: AWS EC2, Nginx, PM2
Other Tools: JWT Authentication, Mongoose, Bcrypt, Axios

⚙️ Key Features
🧩 1. Role-Based Authentication

Vaidyog supports four user roles, each with distinct access levels and dashboards:

Admin: Full control over users, jobs, and platform analytics.

Sub-Admin: Limited admin privileges for managing recruiters and users.

Recruiter: Post and manage healthcare job listings, view analytics, and monitor plan usage.

User (Candidate): Browse and apply for healthcare jobs with personalized filters.

Authentication and access control are implemented securely using JWT tokens and middleware-based role validation.

💼 2. Plan-Based Job Management

Recruiters can post and manage jobs based on their active plan.

Each plan defines limits on:

Number of job posts

Plan validity period

Users’ job applications are also regulated by plan tiers.

Admins can create, update, and assign plans, providing a scalable monetization model.

🔍 3. Advanced Job Search with MongoDB Aggregation

Optimized and efficient search functionality using MongoDB Aggregation Pipelines, allowing multi-criteria filtering on:

Job Title

Work Type

Posted Date

Education

Clinical Role

By leveraging aggregation and indexes, API latency was reduced by 47%, delivering faster and more responsive results.

📊 4. Interactive Charts & Insights

Integrated Chart.js for dynamic visualization:

Active Jobs per Recruiter

Plan Usage and Subscription Statistics

Visually appealing and data-driven dashboards to help admins and recruiters track performance.

🧱 5. Scalable Architecture

Built on MERN stack for modularity and maintainability.

Deployed on AWS EC2 with Nginx reverse proxy and PM2 for process management.

Secure API routes with JWT and environment-based configurations.

🧠 Highlights

✅ 47% faster job search responses via MongoDB aggregations
✅ Secure multi-role authentication with token-based access
✅ Real-time analytics using Chart.js
✅ Plan-based job posting & application limits
✅ Deployed on AWS for reliability and scalability

🌐 Deployment

Frontend: Deployed on AWS EC2, served via Nginx

Backend: Node.js app managed by PM2
