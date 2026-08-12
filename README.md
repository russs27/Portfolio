Portfolio site

What I added
- index.html — simple, responsive portfolio template that loads projects from projects.json
- styles.css — minimal styles for layout and cards
- projects.json — a JSON array you can edit to list your projects
- README.md — this file

How to edit your projects
- Open projects.json and replace the placeholder entries with your real projects.
  Each project is an object with: title, description, tech (array), link (optional), image (optional URL).

Preview locally
- Run a simple static server from this repo root. Example (requires Python):
  - Python 3: python -m http.server 8000
  Then visit http://localhost:8000

Deploy
- Host on GitHub Pages by enabling Pages in repository settings (use main branch / root)
- Or deploy to any static host (Netlify, Vercel, Surge, etc.)

If push to main failed
- If this commit couldn't be applied because the branch is protected or changed, tell me and I will create a branch and open a pull request instead.

Questions or want customization?
- Tell me the projects you want listed (title, description, tech, link, image) and I will update projects.json and improve the layout or add sections (About, Contact, Resume link).

