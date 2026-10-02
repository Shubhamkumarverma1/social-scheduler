# 🚀 Social Scheduler

A full-stack **Social Media Scheduling and AI Content Generation
Platform** that helps users manage social accounts, create engaging
posts with AI, schedule content, and automate their social media
workflow from a single dashboard.

## ✨ Features

-   🔐 **User Authentication**
    -   Secure login and logout
    -   Protected application routes
    -   User-specific dashboard and data
-   👤 **Social Account Management**
    -   Connect and manage social media accounts
    -   View connected accounts from a central dashboard
-   🤖 **AI Content Composer**
    -   Generate social media content using AI
    -   Select different writing styles such as:
        -   Professional
        -   Creative
        -   Funny
        -   Minimalist
        -   Excited
    -   Generate content based on a custom prompt
-   🖼️ **AI Image Generation**
    -   Optional AI-generated images for social posts
    -   Toggle image generation directly from the composer
-   📅 **Post Scheduling**
    -   Create and schedule social media posts
    -   Manage upcoming scheduled content
    -   Keep track of previously created content
-   📊 **Dashboard**
    -   Centralized view of social media activity
    -   View accounts, schedules, and recent generations
-   🔔 **Automation**
    -   Automate social media publishing workflows
    -   Reduce repetitive manual posting

## 🛠️ Tech Stack

### Frontend

-   React.js
-   JavaScript
-   Tailwind CSS
-   React Router
-   Axios
-   Modern responsive UI

### Backend

-   Node.js
-   Express.js
-   REST APIs
-   Authentication & authorization

### Database

-   MongoDB

### AI

-   Google Gemini API
-   AI-powered text generation
-   AI-powered image generation

### Other Technologies

-   Git & GitHub
-   Environment variables
-   RESTful API architecture

## 📁 Project Structure

``` text
social-scheduler/
│
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── server/                 # Node.js + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   └── server.js
│
├── .gitignore
├── README.md
└── package.json
```

> The exact folder structure may vary depending on the implementation.

## ⚙️ Installation

### 1. Clone the repository

``` bash
git clone https://github.com/your-username/social-scheduler.git
cd social-scheduler
```

### 2. Install dependencies

For the frontend:

``` bash
cd client
npm install
```

For the backend:

``` bash
cd ../server
npm install
```

### 3. Configure environment variables

Create a `.env` file inside the backend directory.

Example:

``` env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key
```

Add any additional API keys required by the social media integrations.

**Do not commit your `.env` file to GitHub.**

### 4. Start the backend

``` bash
cd server
npm run dev
```

### 5. Start the frontend

Open another terminal:

``` bash
cd client
npm run dev
```

The application will normally be available at:

``` text
http://localhost:5173
```

## 🔄 Application Workflow

``` text
User Login
    ↓
Dashboard
    ↓
Connect Social Accounts
    ↓
AI Composer
    ↓
Enter Post Prompt
    ↓
Select Content Style
    ↓
Generate AI Content
    ↓
Optional AI Image
    ↓
Schedule Post
    ↓
Scheduled Posts
    ↓
Automatic Publishing
```

## 🤖 AI Content Generation

The AI Composer allows users to describe what they want to publish.

Example:

``` text
Generate a simple Instagram post about learning JavaScript.
```

The user can then choose a writing style:

``` text
Professional | Creative | Funny | Minimalist | Excited
```

The application sends the request to the backend, which communicates
with the configured AI service and returns generated content to the
frontend.

## 🔒 Security

The application follows common security practices including:

-   Protected API routes
-   Authentication and authorization
-   Environment variables for sensitive credentials
-   Secure handling of API keys
-   Server-side API requests
-   `.env` excluded from Git using `.gitignore`

## 🧪 Example Use Case

A user wants to promote a new software project.

They can enter:

``` text
Create an Instagram post announcing my new AI-powered web application.
```

Then select:

``` text
Creative
```

The AI generates the post content. The user can optionally generate an
image and schedule the post for a selected date and time.

## 🚀 Future Improvements

-   Support for more social media platforms
-   Instagram publishing integration
-   LinkedIn publishing integration
-   X/Twitter publishing integration
-   Facebook publishing integration
-   Analytics and engagement tracking
-   Post performance charts
-   Hashtag recommendations
-   AI caption improvement
-   AI content calendar
-   Bulk post scheduling
-   Image and video uploads
-   Team collaboration
-   Role-based access control
-   Production deployment with CI/CD

## 📸 Screenshots

Add screenshots of the application here:

``` text
screenshots/
├── dashboard.png
├── ai-composer.png
├── accounts.png
└── scheduler.png
```

Example:

``` markdown
![AI Composer](screenshots/ai-composer.png)
```

## 🌐 Deployment

The frontend and backend can be deployed using platforms such as:

-   Vercel
-   Render
-   Railway

Before deployment, configure the required environment variables in the
hosting platform.

## 👨‍💻 Author

**Shubham**

MCA \| Full Stack Developer

### Skills Used

`JavaScript` `React.js` `Node.js` `Express.js` `MongoDB` `REST API`
`AI Integration` `Git` `GitHub`

## 📄 License

This project is created for educational and portfolio purposes.

You may modify and extend the project according to your requirements.
