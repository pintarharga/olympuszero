# Olympus Zero — Personal Portfolio

A modern, multi-page personal portfolio website with SPA-like page transitions.

## Structure

```
portfolio/
├── index.html          ← Home (Hero, About preview, Projects, Timeline, Goals)
├── about.html          ← Full About Me + Timeline + Skills
├── projects.html       ← All Projects + Research + Blog
├── achievements.html   ← Awards, Scholarships, Certifications, Skills
├── gallery.html        ← Photo Gallery with filter + lightbox
├── contact.html        ← Contact form + social links
│
├── css/
│   └── style.css       ← All shared styles (dark/light theme, components)
│
├── js/
│   └── script.js       ← All shared JS (routing, animations, transitions)
│
├── assets/
│   ├── images/         ← Your photos (profile, projects, gallery)
│   ├── certificates/   ← Certificate images
│   ├── research/       ← Research documents
│   └── cv/             ← Your CV
│
└── docs/
    └── CV.pdf          ← Your CV (linked from download buttons)
```

## How to Customize

1. **Name & Info**: Search for "Your Name Here" across all HTML files and replace.
2. **Photos**: Drop images in `assets/images/` and update `src` attributes.
3. **CV**: Place your PDF as `docs/CV.pdf`.
4. **Colors**: Edit CSS variables in `css/style.css` under `:root`.
5. **Social Links**: Update `href="#"` links in nav and footer across all pages.

## Deploy

- **GitHub Pages**: Push the folder to a repo, enable Pages from Settings.
- **Netlify**: Drag & drop the portfolio folder on netlify.com/drop.
- **Vercel**: `vercel --cwd portfolio` or import via dashboard.

No build step needed — pure HTML/CSS/JS.

## Features

- ✅ SPA-style smooth page transitions
- ✅ Dark / Light mode toggle (saved to localStorage)  
- ✅ Scroll progress bar
- ✅ Scroll reveal animations
- ✅ Animated counters
- ✅ Animated skill bars
- ✅ Gallery with filter + lightbox
- ✅ Project filter by category
- ✅ Mobile-responsive + hamburger drawer
- ✅ Constellation canvas on hero
- ✅ Back to top button
- ✅ Contact form with feedback
