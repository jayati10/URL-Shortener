# Trimrr - URL Shortener Web App

Trimrr is a full-stack URL shortener built using **React.js**, **Supabase**, **Tailwind CSS**, and **Shadcn UI**. It allows users to generate, manage, and monitor custom short links with secure authentication and real-time database syncing.

## 🚀 Features

- 🔗 Custom URL shortening
- 👤 User authentication (via Supabase)
- 📊 Real-time link tracking and analytics
- 🎨 Responsive and clean UI (Tailwind CSS + Shadcn UI)
- 📁 Personalized dashboard for managing links

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS, Shadcn UI
- **Backend:** Supabase (PostgreSQL, Auth, Realtime)
- **Deployment:** [Add deployment details if hosted]


## 📦 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/trimrr-url-shortener.git
cd trimrr-url-shortener
```
### 1. Install Dependencies
Make sure you have Node.js installed. Then, run:
```bash
npm install
```
### 2. Setup Supabase
- Create a new project on [Supabase](https://supabase.com/)
- Inside the project dashboard, go to **Project Settings > API** to get your project URL and Anon Key
- In the root of your project, create a `.env` file and add:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

### 3. Run the App Locally
Start the development server:
```bash
npm run dev
```

## 🧾 Folder Structure

```
src/
├── components/        # Reusable UI components
├── pages/             # Route-based components
├── utils/             # Utility functions (e.g., API helpers)
├── App.jsx            # Main application component
└── main.jsx           # App entry point
```
