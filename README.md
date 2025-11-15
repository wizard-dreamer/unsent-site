# thewordsleftunsent

A minimal, anonymous confessional web app — a place to whisper what you can’t say aloud.

Mobile-first. Lightweight. Firestore-ready. Perfect for quick deployment on Vercel.

🔗 Quick Links

Live Demo: https://thewordsleftunsent.vercel.app/

Project Folder: unsent/

Key Files: index.html, whispers.html, compose.html, detail.html, assets/

💡 What This Project Does

A simple platform where users can share short, anonymous “whispers.”
The app supports both Firestore real-time sync and a localStorage-only fallback so it works seamlessly whether online or offline.

Users can:

Post confessions anonymously or with a recipient.

Browse a live feed of whispers.

Open detail pages with like & local delete options.

Search whispers by text or recipient.

Enjoy a smooth, mobile-first experience.

✨ Features
📱 Mobile-First UI

Designed with Tailwind CSS for a clean, modern experience that feels great on phones.

🔥 Optional Firestore Integration

Realtime listeners

Auto-update feed

Works instantly if Firestore keys are provided

💾 LocalStorage Fallback

Ideal for testing without any backend setup.

📝 Compose Experience

Recipient, mood, and anonymity toggle

Autosizing textareas

Live preview

Shortcut: Ctrl/Cmd + Enter to post

🔍 Smart Client-Side Search

Find whispers by recipient or text instantly.

❤️ Detail Page Tools

Like button

Delete (local only)

⚡ No Build Step

Entire UI is static—just drop the folder into Vercel and deploy.
