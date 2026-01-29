# Simple Tech Timeline

An interactive timeline showcasing the history of technology from 1957 to 2020. Built with React, TypeScript, and Vite.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.3-61dafb.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178c6.svg)

## 🚀 Features

- **Interactive Timeline** – Navigate through major technological milestones
- **Detailed Event Modals** – Click on events to learn more about each breakthrough
- **Dark/Light Theme** – Toggle between themes for comfortable viewing
- **Responsive Design** – Works seamlessly on desktop and mobile devices
- **Smooth Animations** – Powered by Framer Motion

## 📁 Project Structure

```
Simple-Tech-Timeline/
├── src/
│   ├── components/    # React components
│   │   ├── Header.tsx
│   │   ├── Timeline.tsx
│   │   ├── EventModal.tsx
│   │   ├── EventMarker.tsx
│   │   └── FilterPanel.tsx
│   ├── hooks/         # Custom React hooks
│   │   └── useTheme.ts
│   ├── data/          # JSON data files
│   │   └── events.json
│   ├── styles/        # CSS stylesheets
│   │   └── styles.css
│   ├── utils/         # Utility functions
│   ├── App.tsx        # Main app component
│   ├── main.tsx       # Entry point
│   └── types.ts       # TypeScript types
├── public/            # Static assets
├── docs/              # Documentation
│   └── accessibility.md
├── legacy/            # Legacy JavaScript files
├── index.html         # HTML entry point
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🛠️ Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Simple-Tech-Timeline.git
   cd Simple-Tech-Timeline
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## ▶️ Running the App

### Development Mode

Start the development server with hot reload:

```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or another port if 5173 is in use).

### Production Build

Build the app for production:

```bash
npm run build
```

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
```

## 🧪 Tech Stack

| Technology | Purpose |
|------------|---------|
| [React 18](https://react.dev/) | UI Library |
| [TypeScript](https://www.typescriptlang.org/) | Type Safety |
| [Vite](https://vitejs.dev/) | Build Tool & Dev Server |
| [Framer Motion](https://www.framer.com/motion/) | Animations |

## 📖 Usage

1. Use the timeline slider or click on year labels to navigate through events
2. Click "Learn More" or an event card to view detailed information
3. Toggle the theme button to switch between light and dark modes

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

---

*Built with ❤️ and React*
