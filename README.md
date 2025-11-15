#thewordsleftunsent

A small, anonymous confessional web app — whisper what you can’t say aloud. Mobile-first UI, simple Firestore integration (with localStorage fallback), and ready to deploy to Vercel.

Quick links

Live (example): https://thewordsleftunsent.vercel.app/

Project folder: unsent/

Files to look at: index.html, whispers.html, compose.html, detail.html, assets/

What this project does

Let users write anonymous “whispers” (short confessions).

Show a public feed of whispers (reads Firestore realtime if configured; otherwise local-only).

Compose page with recipient, mood, anonymity, preview, and Ctrl/Cmd+Enter submit.

Detail page with like and local delete functionality.

Mobile-first design (Tailwind CSS), lightweight, no build step required for the static UI.

Features

Mobile-optimized hero, feed, compose, and detail screens.

Realtime Firestore listener for live updates (optional).

LocalStorage fallback for development/testing without a backend.

Client-side search (recipient/text).

Friendly UX: large tap targets, previews, autosize textareas, keyboard shortcuts.


