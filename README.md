
# Hladik Lab Website (hlab.science)

A simple, static website for the Hladik Lab. Built with HTML/CSS and deployed on Netlify.

## Contents
- `index.html` — Home
- `about.html` — Vision, Mission, Motto
- `research.html` — Research themes
- `team.html` — Team profiles
- `publications.html` — Key publications
- `contact.html` — Contact form (Netlify Forms enabled)
- `assets/css/styles.css` — Styles
- `assets/js/scripts.js` — Mobile navigation
- `assets/img/` — Images (replace placeholders)
- `netlify.toml` — Netlify configuration

## Getting Started
1. Replace placeholder images in `assets/img/`:
   - `hero.jpg` — banner image (~1600×900)
   - `profile_placeholder.png` — team headshots
   - `favicon.png` — small square icon
2. Edit text on each page to fit your lab.

## Deploying with GitHub + Netlify

### Create and push the repository
```bash
# from the folder where this README lives
git init
git add .
git commit -m "Initial commit: Hladik Lab site"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/hlab-science.git
git push -u origin main
```

### Link repository to Netlify
1. Log in to Netlify → **Add new site → Import an existing project**.
2. Choose **GitHub**, authorize access, and select your repo.
3. Build settings:
   - **Build command**: *(leave empty)*
   - **Publish directory**: `.`
4. Click **Deploy site**.

### Connect your custom domain (hlab.science)
- In Netlify, go to **Site settings → Domain management → Add custom domain**.
- If Netlify manages DNS (nameservers set to Netlify), SSL is automatic.

## Updating the Site
- Edit files locally, commit, and `git push`. Netlify auto-deploys.
- Check deploy logs under **Deploys** in Netlify.

## Netlify Forms (Contact page)
The contact form includes `data-netlify="true"`. Submissions appear under **Forms** in the Netlify dashboard.

## License
© 2025 Hladik Lab. All rights reserved.
