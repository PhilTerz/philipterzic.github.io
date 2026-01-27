# Personal Site

My personal website hosted on GitHub Pages.

## Structure

```
/                   → Home page
/meals/             → Meal planner app
```

## Setup

1. Create repo on GitHub (e.g., `username.github.io` for user site, or any name for project site)
2. Push this code
3. Enable GitHub Pages in repo Settings → Pages
4. (Optional) Add custom domain via Porkbun

## Local Development

Just open `index.html` in a browser, or use a local server:

```bash
cd ~/personal-site
python3 -m http.server 8000
```

Then visit `http://localhost:8000`
