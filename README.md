# HiredHive - A Full Stack Job Portal

This is a full-stack job portal built using React, Tailwind CSS, Supabase, Clerk, and Shadcn UI. It allows users to browse and filter job listings, manage job applications, and save job listings for later reference. The application integrates authentication using Clerk and leverages Supabase for backend data storage and retrieval.

## Features

- **Job Listings:** Display and filter job listings based on location and company.
- **Search Jobs:** Allows users to search for jobs by title.
- **Pagination:** Jobs are paginated to optimize performance and user experience.
- **Filters:** Filter jobs by location and company.
- **Authentication:** Secure user authentication with Clerk.
- **Responsive UI:** Tailwind CSS and Shadcn UI components ensure a fully responsive and modern design.

## Tech Stack

- **Frontend:** React.js, Tailwind CSS, Shadcn UI
- **Backend:** Supabase (PostgreSQL, authentication, and storage)
- **Authentication:** Clerk for user authentication
- **State Management:** React hooks

## Installation

### Prerequisites

Make sure you have the following installed on your local machine:

- Node.js (v16 or later)
- npm (v7 or later) or yarn

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### Install Dependencies

```bash
npm install
```

### Make sure to create a `.env` file with following variables -

```
VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
VITE_CLERK_PUBLISHABLE_KEY=
```

### Run the Application

```bash
npm run dev
```
