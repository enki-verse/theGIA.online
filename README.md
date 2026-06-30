# The Great I Am (GIA) — Official Website

A premium single-page website for thegia.online

## ✨ Features

- Elegant, dark luxurious design with gold accents
- Fully responsive (mobile-first)
- Smooth scrolling navigation
- Beautiful hero with artistic performance imagery
- Clearly presented values in elegant cards
- "What makes GIA distinct" highlighted section
- Visual gallery representing embodiment, costumes & performance
- Functional email signup form (ready for Mailchimp or Netlify Forms)
- Mobile hamburger menu
- Subtle animations and premium interactions

## 🚀 Quick Deploy (Recommended)

### Option 1: Netlify (Easiest — Recommended)

1. Push this folder to a new GitHub repository
2. Go to [Netlify](https://app.netlify.com) → "Add new site" → "Import from Git"
3. Connect your GitHub repo
4. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: `.` (or leave as `/`)
5. After deploy, go to **Site settings → Domain management** and connect `thegia.online`

Netlify will automatically provide HTTPS and CDN.

### Option 2: GitHub Pages

1. Push to GitHub
2. Go to repo **Settings → Pages**
3. Source: Deploy from a branch → `main` / `master`
4. Save. Your site will be available at `https://yourusername.github.io/thegia-website`

Then point your domain `thegia.online` via DNS (A record or CNAME) to GitHub Pages.

## 📧 Email Signup (Mailchimp)

The current form is a beautiful frontend experience. To connect real email collection:

### Recommended: Use Netlify Forms (works instantly)

1. Add `data-netlify="true"` and `name="signup"` to the `<form>` tag
2. Redeploy
3. Submissions will appear in your Netlify dashboard → Forms
4. You can then connect a notification email or webhook to Mailchimp / Zapier

### Alternative: Mailchimp Embed

1. Log into Mailchimp → Audience → Signup forms → Embedded forms
2. Copy the generated form code
3. Replace the entire `<form id="signup-form">...</form>` block in `index.html` with Mailchimp's code
4. Style it to match (the current classes are easy to adapt)

The form currently shows a success state instantly. Replace the JavaScript submit handler when you connect the real backend.

## 🎨 Customization

- **Images**: Replace `hero-performance.jpg` and `costumes-carnival.jpg` with your own high-quality photos from the camp.
- **Colors**: Gold accent is `#c9a227`. Change in the CSS custom properties or Tailwind classes.
- **Content**: All text is easy to edit directly in `index.html`.
- **Navigation**: Currently uses smooth scroll anchors. A full top nav can be expanded later.

## 📁 File Structure

```
thegia-website/
├── index.html          # The complete single page site
├── hero-performance.jpg
├── costumes-carnival.jpg
└── README.md
```

## 💡 Future Enhancements (when ready)

- Add real navigation with active section highlighting
- Integrate actual Mailchimp or ConvertKit
- Add a simple events or upcoming workshops section
- Password-protected member area later
- Blog or writings section

## Need help?

This site was built to feel premium, intentional, and aligned with the magical, embodied spirit of GIA.

You can edit everything in `index.html`. It's a single file so it's easy to maintain.

Welcome to the circle.

—The Great I Am