# MCOE Pulse

Clubs, chapters and events portal for MCOE (Student and Club Member roles).

## Files
- `index.html` home, `clubs.html`, `events.html`, `login.html`
- `student.html` student dashboard, `workspace.html` club member workspace
- `style.css` all styling, `app.js` all logic and data

## Run
Open `index.html` in a browser, or publish the folder with GitHub Pages (Settings > Pages > main branch).

## Notes
- Data (accounts, events, registrations, saved clubs) lives in the browser's localStorage. This is a front-end demo; passwords are not secure.
- Chapters, clubs and activities (29 + 9 more incl. Astronomy Club, Art Circle, M-Pulse, Karmanya, NSS, Sports) come from the official MCOE site, each with an official page link. Descriptions, categories, quiz matches and most events are sample content.
- For real shared data, connect a backend such as Supabase or Firebase.
