# Jaydon Ford — Portfolio Site

A single self-contained page: `index.html` has all the HTML, CSS, and JS in one file. No build tools, no dependencies to install.

## Publish it for free with GitHub Pages

1. Create a GitHub account if you don't have one: https://github.com/signup
2. Create a new repository. Name it `your-username.github.io` (replace `your-username` with your actual GitHub username) — this exact naming makes GitHub host it automatically.
3. Upload `index.html` to that repository (use the "Add file → Upload files" button on the repo page — no command line needed).
4. Go to the repo's **Settings → Pages**. Under "Source," pick the `main` branch and save.
5. Wait a minute, then visit `https://your-username.github.io` — your site is live.

If you'd rather not use your username as the site name, you can name the repo anything (e.g. `portfolio`) and the site will be published at `https://your-username.github.io/portfolio` instead.

## Editing content

Open `index.html` in any text editor and scroll to the `<script>` section near the bottom. Four arrays control the dynamic sections:

- `timeline` — your journey, in order
- `certifications` — cert cards
- `projects` — leave empty for the placeholder state, or add entries as you build things
- `journal` — short dated log entries

Add an entry by copying the commented-out example line in each array and filling in your own text. Everything else (nav, hero text, about, contact links) is plain HTML you can edit directly — search for the text you want to change.

Before publishing, update the placeholder email, LinkedIn URL, and resume link in the Contact section.
