# Zurvan: Master Infinite Progress

> Infinite time. Finite focus. One dashboard.

A sophisticated personal learning command center that transforms how you track, manage, and optimize your learning journey across multiple streams. ZURVAN combines beautiful design with powerful analytics to help you master your educational pursuits.

![Dashboard Screenshot](https://storage.googleapis.com/aifire.appspot.com/screenshots/zurvan-dashboard.png)

## 🎯 Why ZURVAN?
Traditional learning trackers are either too simplistic or overly complex. ZURVAN strikes the perfect balance with:

*   **Unified Dashboard** - See all your learning streams in one glance.
*   **Intelligent Prioritization** - High-level overview of daily tasks to guide your focus.
*   **Visual Progress Tracking** - Animated metrics that motivate and inform.
*   **Evidence-Based Learning Ready** - The architecture is ready for screenshot and proof integration.
*   **Time-Aware Analytics** - Understand your learning patterns at a glance.

## ✨ Features Implemented

#### 🎨 Core Experience
*   ✅ **Beautiful Floating Stream Cards** - Interactive cards for IBM Bootcamp, Red Hat Academy, Skillsoft Percipio, and a Computer Science Degree.
*   ✅ **Today's Focus Priorities** - Smart daily task prioritization with progress tracking.
*   ✅ **Animated Progress Metrics** - Live charts and visual progress indicators for streams and weekly activity.
*   ✅ **Responsive Design** - Flawless experience across all devices.
*   ✅ **Modern UI/UX** - Clean, professional interface with smooth animations via Framer Motion.

#### 🔐 Authentication & Data
*   ✅ **User Authentication** - Secure Firebase Authentication system for user sign-in and sign-up.
*   ✅ **Basic Navigation Structure** - Intuitive app navigation from the main dashboard to stream detail pages.
*   ✅ **Real-time Updates** - The app is structured for live data synchronization with Firestore.

#### 🤖 AI Integration
*   ✅ **AI Insights Ready** - Genkit integration is in place for personalized learning recommendations.
*   ✅ **Smart Analytics** - The foundation is set for pattern recognition and progress analysis.

## 🚧 Current Development Focus
*   **In Progress**
    *   **Firestore Integration** - Connecting the UI components to a persistent Firestore database to replace the current mock data.
    *   **Stream Detail Pages** - Fleshing out the comprehensive stream-specific views.
    *   **Focus Timer** - Implementing a Pomodoro-style focus session timer with analytics.
*   **Planned Features**
    *   **Proof Upload System** - Drag-and-drop screenshot evidence for tasks.
    *   **Advanced Analytics** - AI-powered deep learning insights and recommendations.

## 🛠 Tech Stack
*   **Frontend**
    *   Next.js 14 - React framework with App Router
    *   TypeScript - Type-safe development
    *   Tailwind CSS - Utility-first styling
    *   Framer Motion - Smooth animations and interactions
*   **Backend & Services**
    *   Firebase Authentication - Secure user management
    *   Firestore Database - Real-time data persistence
*   **AI & Analytics**
    *   Genkit - AI integration framework
    *   Google Gemini - Advanced AI insights and recommendations

## 🚀 Getting Started
#### Prerequisites
*   Node.js 18+
*   A Firebase project with Authentication and Firestore enabled.

#### Installation
1.  **Clone the repository**
    ```bash
    git clone https://github.com/kwisdomk/zurvan-tracker.git
    cd zurvan-tracker
    ```
2.  **Install dependencies**
    ```bash
    npm install
    ```
3.  **Environment setup**
    *   You will need to have a `firebaseConfig` object in `src/firebase/config.ts`. The current setup uses a placeholder.
4.  **Run development server**
    ```bash
    npm run dev
    ```
5.  **Open your browser** to `http://localhost:3000` (or the specified port).

## 🏗 Project Structure
```text
zurvan-tracker/
├── src/
│   ├── app/                    # Next.js app router
│   │   ├── page.tsx           # Main dashboard
│   │   ├── signin/page.tsx    # Sign-in page
│   │   └── streams/[id]/      # Stream detail pages
│   ├── components/            # React components
│   │   ├── floating-stream-cards.tsx
│   │   ├── today-focus.tsx
│   │   ├── animated-metrics.tsx
│   │   └── ui/                # Reusable ShadCN UI components
│   ├── firebase/              # Firebase configuration and hooks
│   ├── hooks/                 # Custom React hooks
│   ├── lib/                   # Utilities and configurations
│   └── ai/                    # Genkit flows for AI features
└── public/                    # Static assets
```

## 🤝 Contributing
ZURVAN is currently a personal project. While not open for external contributions at this time, the architecture is designed for future scalability and potential open-source development.

## 📄 License
This project is currently for personal use. Licensing for future open-source release is under consideration.

## 🙏 Acknowledgments
This project has been built and iterated upon with the assistance of a cutting-edge AI development environment, combining AI assistance with modern web development practices.

---

***ZURVAN - Transforming learning tracking from chore to command center. Because your education deserves more than a spreadsheet.***
