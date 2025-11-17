# 💼 Job Portal

A full-stack **Job Portal** built with **Next.js**, **MongoDB**, and **Clerk Authentication**. Designed for two primary user roles — **Candidates** and **Recruiters**, this application enables job seekers to find and apply for jobs while allowing recruiters to post and manage job listings.

---

## 🚀 Live Demo

👉 https://next-js-job-portal-murex.vercel.app/

---

## 👥 User Roles & Features

### 🧑‍💼 Candidates:
- Create and edit profile
- Upload resumes
- Browse and filter job listings
- Apply for jobs directly

### 🧑‍💻 Recruiters:
- Create and manage job listings
- View and manage job applications
- Browse candidate profiles

---

## ✨ Highlight Features

- 🔐 **Authentication & Authorization**: Secure sign-up/login via **Clerk**
- 🧭 **Role-Based Dashboard**: Users access features specific to their role
- 🗂 **Membership System**: Premium recruiters can post more jobs; free-tier users have limits
- 🔍 **Job Filtering**: Search and filter jobs by title, location, and type
- 💾 **MongoDB Integration**: Stores all job listings, user profiles, and applications
- ⚡ **Server Actions**: Handles backend logic seamlessly without traditional API routes
- 🧑‍🎓 **Responsive UI**: Clean, mobile-friendly user experience

---

## 🧰 Tech Stack

| Technology     | Description                                  |
|----------------|----------------------------------------------|
| Next.js        | Full-stack React framework (App Router)      |
| MongoDB        | NoSQL database for user/job data             |
| Clerk Auth     | Authentication and user session management   |
| Tailwind CSS   | Utility-first CSS for fast styling           |
| React Hook Form| Forms and validations                        |


⚙️ Environment Variables

Create a .env.local file in the project root:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key

CLERK_SECRET_KEY=your_key

NEXT_PUBLIC_SUPABASE_URL=your_url

NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key

SUPABASE_SERVICE_ROLE_KEY=your_key

STRIPE_SECRET_KEY=your_stripe_secret

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_public

STRIPE_WEBHOOK_SECRET=your_webhook_secret

MONGODB_URI=your_mongo_uri


🛠️ Installation

Clone the repo:

git clone <your-repo-url>

cd job-board


Install dependencies:

npm install

▶️ Development

npm run dev


App runs at:

http://localhost:3000

## screenshots

# Home 

<img width="1313" height="716" alt="image" src="https://github.com/user-attachments/assets/31ba32ee-32a9-4633-9ff2-6e016d7eac0b" />

# Login

<img width="1302" height="545" alt="image" src="https://github.com/user-attachments/assets/5af1d132-2b58-4ede-a69f-e5c38f4ba3f3" />

# Job board

<img width="1305" height="549" alt="image" src="https://github.com/user-attachments/assets/a170719a-7ef7-4051-b617-cbb1c1544238" />

# memebership

<img width="1292" height="608" alt="image" src="https://github.com/user-attachments/assets/f21fb9d7-f555-46ac-9717-c7c93263e814" />

