# Past the Click — Website

pasttheclick.com

## Files

- `index.html` — main page
- `style.css` — all styles
- `main.js` — scroll nav + reveal animations
- `CNAME` — custom domain for GitHub Pages

## Deploy to GitHub Pages

1. Create a new GitHub repository (public)
2. Push all files to the `main` branch
3. Go to Settings → Pages
4. Set Source to "Deploy from branch" → main → / (root)
5. Add custom domain: `pasttheclick.com`
6. Enable "Enforce HTTPS"

## Point your domain at GitHub Pages

At your domain registrar (Namecheap / Cloudflare / GoDaddy),
add these DNS records:

**A records (point @ to GitHub):**
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

**CNAME record:**
www → your-github-username.github.io

Changes propagate within 1-24 hours.

## Update the calendar link

In `index.html`, replace the Google Calendar link with your
actual Google Calendar appointment scheduling URL:

```
<a href="YOUR_CALENDAR_LINK" target="_blank" ...>
```

## Colors

| Name     | Hex       |
|----------|-----------|
| Ink      | #141210   |
| Ember    | #e85d26   |
| Chalk    | #f8f7f4   |
| Parchment| #f0ede6   |
| Stone    | #c8c4bc   |
| Dust     | #b0ab9e   |
| Deep     | #111009   |
| Charcoal | #3a3830   |
