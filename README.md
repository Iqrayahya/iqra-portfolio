# Iqra Yahya: Portfolio Website

Personal portfolio for Iqra Yahya, who creates AI video, builds AI agents and automates workflows with Claude Code.

A single static page: plain HTML, CSS and a little JavaScript. No build step and no dependencies.

## Structure

```
index.html     the whole site (styles and scripts included)
images/        portrait, project screens and ad cover frames
videos/        web versions of the client ads (H.264, 540p)
```

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the `main` branch and the `/ (root)` folder, then save.

The site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Editing

- **Social links and email:** the `LINKS` object near the bottom of `index.html`.
- **Contact form:** set `FORM_ENDPOINT` (for example, a Formspree URL) so messages are actually sent. Until it is set, the form copies the visitor's message so they can send it on WhatsApp, Instagram or email.

© 2026 Iqra Yahya. All rights reserved.
