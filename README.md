# SDP Redirect

This repository contains a simple redirect page that redirects visitors from `republicofjulia.org/sdp` to our Discord server.

## Deployment

This site is designed to be deployed using GitHub Pages.

### Setup Instructions:

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Set source to "Deploy from a branch" → main branch
4. Your site will be available at `https://yourusername.github.io/sdp`
5. Configure your custom domain `republicofjulia.org` to point to GitHub Pages

### Custom Domain Setup:

1. In your domain registrar, create a CNAME record:
   - Name: `sdp` (or `@` for root domain)
   - Value: `yourusername.github.io`
2. In GitHub Pages settings, add your custom domain: `republicofjulia.org`

## Features

- Instant redirect to Discord server
- Multiple redirect methods for maximum compatibility
- User-friendly loading page with fallback link
- Mobile responsive design