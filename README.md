# AI-Powered LMS with Real-Time Voice Intelligence

A modern Learning Management System (LMS) built with Next.js, Clerk Authentication, Supabase, and Vapi AI. The platform enables users to learn through AI-powered voice interactions, track progress, manage subscriptions, and interact with intelligent learning companions in real time.

## Features

* AI-powered voice learning companions
* Real-time voice interactions and transcription
* Secure authentication with Clerk
* Course progress tracking
* Bookmark and personalized learning features
* Subscription and billing management
* Responsive and modern user experience
* Error monitoring with Sentry

---

## Screenshots

### Home Page
![Home Page](public/screenshots/Home.png)

### Companions Page
![Companions Page](public/screenshots/companions.png)

### Companion Learner View
![Companion Learning View](public/screenshots/Learning.png)

### User Profile
![User Profile](public/screenshots/userprofile.png)

### Subscription Page
![Subscription Page](public/screenshots/subscription.png)

---

## Tech Stack

### Frontend

* Next.js 15
* React 19
* TypeScript
* Tailwind CSS

### Authentication

* Clerk

### Database

* Supabase

### AI & Voice

* Vapi AI

### Monitoring

* Sentry

### Form Validation

* React Hook Form
* Zod

---

## Installation

### Clone the Repository

```bash
git clone <repository-url>

cd js_saas_app
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file and configure:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

SENTRY_AUTH_TOKEN=
```

### Run Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## Production Build

```bash
npm run build
```

```bash
npm start
```

---

## Available Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
```

