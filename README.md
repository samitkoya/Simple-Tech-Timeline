# Simple Tech Timeline

An interactive timeline showcasing the history of technology from 1957 to 2020. Built with React, TypeScript, and Vite.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.3-61dafb.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178c6.svg)
![Vite](https://img.shields.io/badge/Vite-5.2-646cff.svg)

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
│   ├── components/         # React UI components
│   │   ├── EventMarker.tsx
│   │   ├── EventModal.tsx
│   │   ├── FilterPanel.tsx
│   │   ├── Header.tsx
│   │   └── Timeline.tsx
│   ├── data/               # JSON data files
│   │   └── events.json
│   ├── hooks/              # Custom React hooks
│   │   └── useTheme.ts
│   ├── styles/             # CSS stylesheets
│   │   └── styles.css
│   ├── utils/              # Utility functions
│   │   ├── fetcher.ts
│   │   ├── index.ts
│   │   ├── modal.ts
│   │   ├── renderer.ts
│   │   └── theme.ts
│   ├── App.tsx             # Main app component
│   ├── main.tsx            # Entry point
│   └── types.ts            # TypeScript type definitions
├── public/                 # Static assets
│   └── first.jpg
├── docs/                   # Documentation
│   └── accessibility.md
├── legacy/                 # Legacy JavaScript files (deprecated)
│   ├── fetcher.js
│   ├── index.js
│   ├── modal.js
│   ├── renderer.js
│   ├── script.js
│   ├── theme.js
│   └── types.js
├── node_modules/           # Installed dependencies (auto-generated)
├── index.html              # HTML entry point
├── package.json            # Project dependencies & scripts
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite configuration
└── LICENSE                 # MIT License
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

## 📋 Dependencies

### Production Dependencies

| Package | Version | Description |
|---------|---------|-------------|
| [react](https://react.dev/) | ^18.3.1 | UI Library |
| [react-dom](https://react.dev/) | ^18.3.1 | React DOM rendering |
| [framer-motion](https://www.framer.com/motion/) | ^11.18.2 | Animation library |

### Development Dependencies

| Package | Version | Description |
|---------|---------|-------------|
| [typescript](https://www.typescriptlang.org/) | ^5.3.3 | Type safety |
| [vite](https://vitejs.dev/) | ^5.2.0 | Build tool & dev server |
| [@vitejs/plugin-react](https://vitejs.dev/) | ^4.2.0 | React plugin for Vite |
| [@types/react](https://www.npmjs.com/package/@types/react) | ^18.3.1 | React type definitions |
| [@types/react-dom](https://www.npmjs.com/package/@types/react-dom) | ^18.3.1 | React DOM type definitions |

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

## 📖 Usage

1. Use the timeline slider or click on year labels to navigate through events
2. Click "Learn More" or an event card to view detailed information
3. Toggle the theme button to switch between light and dark modes
