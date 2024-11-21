Hirrd - Job Fast Search
Hirrd is a job-searching platform designed to simplify the job application process for users and streamline applicant tracking for companies. With robust authentication, an intuitive user interface, and scalable backend infrastructure, Hirrd ensures a seamless experience for all stakeholders.

Table of Contents
Features
Technologies Used
Installation and Setup
Project Architecture
Usage
Future Scope
Contributing
License
Features
For Job Seekers
User-friendly authentication using Clerk (Google, email, etc.).
Browse and apply for jobs with detailed descriptions and images.
Track applied jobs in the "Applied Jobs" section.
Save jobs to a personal wishlist for later consideration.
For Companies
Create and manage job postings with full details, including job descriptions, locations, and images.
View and manage applicants with downloadable resumes.
Change the status of applications to "Interviewing," "Selected," or "Rejected."
Close applications or delete job postings as required.
Additional Features
Modern UI built with ShadCN for a visually appealing and responsive design.
Authentication powered by Clerk, integrated with Supabase for data storage and retrieval.
Secure and scalable architecture for handling large volumes of data and users.
Technologies Used
Frontend
React.js: Framework for building the user interface.
ShadCN: Component library for consistent and modular design.
Backend
Node.js: Backend runtime for scalable server-side processing.
Supabase: Used for database management and seamless integration with authentication.
Authentication
Clerk: Provides a secure and customizable authentication mechanism.
Database
PostgreSQL (via Supabase): Robust relational database for storing user, job, and application data.
Installation and Setup
Prerequisites
Ensure the following are installed on your system:

Node.js (v16 or later)
NPM or Yarn
PostgreSQL (optional if using Supabase)
Git
Clone the Repository
bash
Copy code
git clone https://github.com/your-username/hirrd.git
cd hirrd
Install Dependencies
bash
Copy code
npm install
Environment Variables
Create a .env file in the root directory and configure the following:

env
Copy code
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
CLERK_FRONTEND_API=your_clerk_frontend_api
Start the Development Server
bash
Copy code
npm start
The application will run on http://localhost:3000.