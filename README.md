# I.M. Consulting FZ — Website

Professional website for I.M. Consulting FZ, a specialized engineering and strategic consultancy firm providing solutions for the fluid handling and MEP sectors.

## Pages

- **Home** — Hero, trust metrics, services overview, industries, global reach preview, CTA
- **About** — Company story, operational model, key differentiators
- **Services** — Engineering consultancy, strategic advisory, compliance support with process timeline
- **Industries** — Plumbing, fire protection, water management, electromechanical
- **Global Reach** — Interactive map with partner countries (UAE, China, Taiwan, Czech Republic, Italy)
- **Contact** — Form with subject dropdown, full contact details, WhatsApp integration

## Tech Stack

- Pure HTML, CSS, JavaScript (no build tools required)
- Google Fonts: Playfair Display + DM Sans
- Scroll-reveal animations via Intersection Observer
- Fully responsive (mobile-first)
- GitHub Pages compatible

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your repository
4. Under "Source", select **Deploy from a branch**
5. Choose the **main** branch and **/ (root)** folder
6. Click Save — your site will be live in 1-2 minutes at `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Customization Checklist

Before going live, replace these placeholder values:

- [ ] Phone number: Search for `+971 XX XXX XXXX` and replace with real number
- [ ] Email: Replace `info@imconsultingfz.com` with actual email
- [ ] WhatsApp: Replace `971000000000` in WhatsApp links with real number
- [ ] Office address: Replace `UAE Free Zone` with actual address
- [ ] Images: Replace placeholder image divs with real `<img>` tags
- [ ] Statistics: Verify the numbers in the trust bar (countries, years, projects)
- [ ] Contact form: Connect to a form service (Formspree, Netlify Forms, etc.)
- [ ] Logo: Replace the text logo with an actual logo image if available
- [ ] Analytics: Add Google Analytics tracking code

## Form Integration

The contact form currently simulates submission. To make it functional:

**Option A — Formspree (easiest):**
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form and copy your form ID
3. Change the form tag to: `<form action="https://formspree.io/f/YOUR-ID" method="POST">`
4. Remove the JavaScript form handler in `js/main.js`

**Option B — Netlify Forms (if hosting on Netlify):**
1. Add `netlify` attribute to the form tag: `<form name="contact" netlify>`
2. Deploy to Netlify

## License

All rights reserved. Built for I.M. Consulting FZ.
