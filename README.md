# AI Career Coach - Full Stack Application

## 🚀 Project Overview
An intelligent career coaching platform built with modern tech stack that provides personalized career guidance, industry insights, and interview preparation support using AI.

## 🛠️ Tech Stack
- **Frontend**: Next.js 15.x
- **Backend**: Next.js API Routes
- **Database**: Neon PostgreSQL with Prisma ORM
- **Authentication**: Clerk
- **AI Integration**: Google Gemini AI
- **Styling**: Tailwind CSS, Shadcn UI
- **Background Jobs**: Inngest
- **Other Tools**: 
  - React Hook Form
  - Zod (validation)
  - React Markdown
  - HTML2PDF.js
  - Recharts (for data visualization)
  - Next-themes (dark mode support)

## ✨ Key Features
1. **User Authentication**
   - Secure sign-up/sign-in flow using Clerk
   - Custom onboarding process

2. **Industry Insights**
   - Coverage of 50+ industries
   - Detailed sub-industry categorization
   - AI-powered industry analysis including:
     - Salary ranges
     - Growth rates
     - Demand levels
     - Required skills
     - Market outlook
     - Key trends

3. **Interview Preparation**
   - 1000+ interview questions
   - AI-powered response generation
   - 24/7 AI support

4. **Career Analytics**
   - Interactive charts and visualizations
   - Progress tracking
   - Success rate monitoring

5. **Automated Background Processing**
   - Weekly industry insights generation using Inngest
   - Automated data updates

## 🔧 Environment Setup
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
DATABASE_URL=
GEMINI_API_KEY=
```

## 📦 Installation
```bash
# Install dependencies
npm install

# Generate Prisma client
npx prisma generate

# Run development server
npm run dev
```

## 🏗️ Project Structure
- `/app` - Next.js application routes and pages
- `/components` - Reusable UI components
- `/lib` - Utility functions and configurations
- `/data` - Static data like industry listings
- `/prisma` - Database schema and migrations

## 🎯 Core Functionalities
1. **Industry Analysis System**
   - Automated weekly insights generation
   - Real-time data processing
   - JSON-structured industry data

2. **User Interface**
   - Responsive design
   - Dark mode support
   - Modern UI components from Shadcn

3. **Data Visualization**
   - Interactive charts
   - Statistical representations
   - Progress tracking

## 🔐 Security Features
- Secure authentication with Clerk
- Environment variable protection
- Database connection security

## 💡 Performance Features
- Turbopack for fast development
- Optimized build process
- Efficient data caching

## 🤝 Contributing
Feel free to contribute to this project by:
1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Pushing to the branch
5. Creating a new Pull Request

## 📄 License
This project is private and proprietary.

## 👨‍💻 Developer
Made with 💗 by Prakash & Rajvi

