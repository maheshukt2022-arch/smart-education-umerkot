# Smart Education Umerkot

A responsive, mobile-friendly education web app prototype.

## Run it
- Open `index.html` in a browser, or
- Deploy the folder to GitHub Pages, Netlify, or Vercel (static hosting).

## Included
- Responsive student dashboard
- AI Ustad chat interface with built-in educational explanations
- Six subject areas
- Interactive 5-question quiz with scoring
- Progress saved in browser localStorage
- Free study resource links

## Important AI note
The AI Ustad currently includes built-in answers for common learning topics and a guided fallback. It does not call a live AI model until you configure a provider/API key. Never put a private API key in browser JavaScript. For production, create a server-side endpoint and store the key in an environment variable.

## Next production steps
1. Add authentication and a database for student accounts.
2. Connect a server-side AI provider endpoint.
3. Add verified Umerkot school data and an admin dashboard.
4. Add privacy policy, moderation, backups and deployment domain.
