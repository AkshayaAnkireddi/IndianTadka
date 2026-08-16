# Indian Tadka Website — Deployment Guide

## What is included
- `index.html` — redesigned responsive website
- No build step or framework is required
- The site includes scroll reveals, cinematic hero food transitions, cursor-based 3D movement, menu filtering, full-menu accordion, map, click-to-call buttons, and SEO metadata

## Recommended deployment
GitHub → Vercel → `indiantadka309.com`

### Option A: No Terminal
1. Create/sign in to a GitHub account.
2. Create a new repository named `indian-tadka-website`.
3. Upload `index.html` and commit the change.
4. In Vercel, import the GitHub repository.
5. Deploy. This is a plain static HTML site, so there is no build command to configure.
6. After deployment, add `indiantadka309.com` in Vercel's Domains settings and follow the DNS records Vercel gives you.

### Option B: GitHub Desktop
Install GitHub Desktop, create a repository from this folder, then publish it to GitHub. Connect that repository to Vercel.

### Terminal
Terminal is optional for this project. If you later want to use Git locally:

```bash
git init
git add .
git commit -m "Revamp Indian Tadka website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/indian-tadka-website.git
git push -u origin main
```

## Before the final public launch
Replace the Unsplash food images in `index.html` with Indian Tadka's own dish/interior photos. The current image URLs are placeholders for the visual design.

Also verify the restaurant's phone number, hours, buffet details, prices, and address before publishing.

## SEO / traffic
The page includes a title, description, canonical URL, Open Graph metadata, keyword metadata, and Restaurant structured data. These help search engines understand the site but do not guarantee rankings.

For ongoing traffic, the next upgrades should be: Google Business Profile website link, Google Search Console, real restaurant photography with descriptive alt text, a menu page that search engines can crawl, and periodic updates for specials/buffet information.
