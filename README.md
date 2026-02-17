# SkillSphere — Minimal Starter

This workspace contains an initial scaffold for SkillSphere: a Vite + React + TypeScript frontend with Tailwind, and starter Firebase emulator configuration and Cloud Function.

Quick setup (Windows PowerShell):

```powershell
# 1) Install dependencies
npm install

# 2) Start the Vite dev server
npm run dev

# 3) (Optional) Start Firebase emulators (requires Firebase CLI and a configured project)
npm run emulators
```

Next steps:
- Run the app, confirm dev server runs.
- Add Firebase project credentials in `src/firebaseConfig.ts` or use environment variables.
- I will continue implementing auth, Firestore schema, and UI modules next.
