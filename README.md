# Haripriya G — Portfolio Website

A single-file, fully responsive portfolio website built in pure HTML/CSS/JavaScript.

## File Structure

```
haripriya-portfolio/
└── index.html        ← Complete portfolio (all HTML, CSS, JS in one file)
```

## Features
- Dark / Light mode toggle
- Fully responsive (mobile, tablet, desktop)
- Animated skill progress bars (triggered on scroll)
- Smooth scroll + sticky nav with active section highlighting
- Scroll-to-top button
- Contact form (mailto-based)
- SEO meta tags + Open Graph

## Setup (Local)

1. Download `index.html`
2. Open it directly in any browser — no dependencies or build step needed.

## Deployment

### GitHub Pages (Free)
1. Create a new GitHub repo (e.g. `haripriya-portfolio`)
2. Push `index.html` to the repo root (rename to `index.html` if needed)
3. Go to **Settings → Pages → Branch: main / root**
4. Your site: `https://haripriyaguru.github.io/haripriya-portfolio/`

### Netlify (Free, Recommended)
1. Go to https://app.netlify.com → "Add new site" → "Deploy manually"
2. Drag and drop the `index.html` file
3. Your site is live instantly with a `.netlify.app` URL

### Vercel (Free)
1. Go to https://vercel.com → "New Project"
2. Upload or connect the repo
3. No config needed — auto-detected as static HTML

## Customization

| Section | What to Change |
|---------|---------------|
| Resume download | Replace the Google Drive URL in the hero CTA button |
| GitHub / LinkedIn | Update the URLs in the contact section and footer |
| Projects | Edit project card content in the Projects section |
| Profile photo | Replace the initials `HG` div with an `<img>` tag |

## Future Enhancements

1. **Add a real photo** — replace the `.hero-avatar` initials circle with your headshot
2. **Blog section** — add a `/blog` page linking to Medium or Dev.to articles
3. **Testimonials** — add a section with quotes from peers/mentors
4. **Animated background** — add a particle or constellation canvas to the hero
5. **Project demo videos** — embed short Loom/YouTube clips inside project cards
6. **Analytics** — add Google Analytics or Plausible for visitor tracking
7. **Custom domain** — point your GitHub Pages/Netlify site to a custom domain (e.g. `haripriya.dev`)
