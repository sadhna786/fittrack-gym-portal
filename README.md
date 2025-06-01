# FitTrack Gym Portal 🏋️‍♂️

FitTrack Gym Portal is a modern fitness tracking application built with **React**, **TypeScript**, and **Supabase**. The platform provides an engaging, responsive dashboard to track physical and mental fitness metrics, visualize progress through charts, and manage schedules with an interactive calendar.

## 🚀 Features
- 📊 **Interactive Dashboard:** Visualize your fitness data with **Recharts** and **Chart.js**.
- 🧠 **Mental Health Tracking:** Tools for tracking and improving mental well-being.
- 🗓 **Workout Calendar:** Schedule and track gym sessions.
- 🔐 **User Authentication & Database:** Managed through **Supabase**.
- 💅 **Responsive & Animated UI:** Built with **Tailwind CSS** and **Framer Motion**.

## 🛠 Tech Stack
- **Frontend:** React 18 + TypeScript + Vite
- **State Management & Routing:** React Router Dom
- **Animations:** Framer Motion
- **Styling:** Tailwind CSS
- **Charts & Data Visualization:** Recharts, Chart.js, React ChartJS-2
- **Authentication & Database:** Supabase
- **Tooling:** ESLint, PostCSS

## 📦 Getting Started

### Prerequisites
- Node.js and npm installed
- Supabase project with keys (set up environment variables)

### Installation
```bash
git clone https://github.com/sadhna786/fittrack-gym-portal.git
cd fittrack-gym-portal
npm install
```

### Running Locally
```bash
npm run dev
```

## Building for Production
```bash
npm run build
npm run preview
```

## Project Structure
```bash
fittrack-gym-portal/
├── public/              # Static files
├── src/                 # React components, pages, styles
├── .env                 # Environment variables (Supabase keys, etc.)
├── vite.config.ts       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── package.json         # Project metadata and dependencies
```

## 🔐 Environment Variables
Add a .env file in the root directory with:
```bash
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🤝 Contributing
Contributions are welcome! Fork the repository, create a feature branch, and submit a pull request.

## 📜 License
This project is licensed under the MIT License.
