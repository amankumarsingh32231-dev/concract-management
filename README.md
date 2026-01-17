# Contract App

This is a minimal Vite + React project containing the Contract Management Platform demo.

Quick start (Windows PowerShell):

```powershell
# 1. Install dependencies
npm install

# 2. Start dev server
npm run dev
```

Open the Local URL printed by Vite (typically http://localhost:5173/) to view the app.

Notes:
- Tailwind CSS is configured in `tailwind.config.js` and `src/index.css`.
- Icons use `lucide-react`.
- The action→status mapping bug has been fixed in `src/App.jsx` (see `actionToStatus`).
