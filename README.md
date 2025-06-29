# Hirix - Modern Job Portal Application

Hirix is a modern job portal that connects job seekers with employers and helps employers find bright candidates.

![image](https://github.com/user-attachments/assets/880ce9d7-ae47-485e-851f-2c7b6077635c)
![image](https://github.com/user-attachments/assets/629ed9eb-9185-482e-8e0f-6669dd908f78)

## Features

### For Job Seekers

- Search and apply for jobs with ease
- Track application status
- Save jobs for later
- Upload and manage resumes
- Detailed job descriptions and company information

### For Employers

- Post and manage job listings
- Review candidate applications
- Company profile management
- Track hiring progress

## Tech Stack

- **Frontend**: React 18 with Vite
- **UI Components**: Radix UI with Tailwind CSS
- **Authentication**: Clerk
- **Form Handling**: React Hook Form with Zod validation
- **Markdown Support**: MDEditor for rich text editing
- **State Management**: React Hooks
- **Routing**: React Router v6

## Getting Started

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
```

4. Start the development server:

```bash
npm run dev
```

## Project Structure

- `/src/components` - Reusable UI components
- `/src/pages` - Main application pages
- `/src/api` - API integration layer
- `/src/hooks` - Custom React hooks
- `/src/utils` - Utility functions
- `/src/layouts` - Layout components
- `/public` - Static assets
