# [PRODUCT_NAME] — Landing Page

AI-powered fashion assistant landing page built with Jekyll, deployable on GitHub Pages.

## Local Setup

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Configuration

All content is managed in `_config.yml`. Update placeholders:

- `title` — your product name
- `mailchimp_url` — your Mailchimp form action URL
- `buymeacoffee_url` — your Buy Me a Coffee page URL
- `accent_color` — primary accent color (default: dusty rose `#D4A5A5`)

## Deployment

Push to GitHub, then go to **Settings > Pages** and deploy from the main branch.

## Mailchimp Integration

Replace the `<!-- REPLACE WITH MAILCHIMP EMBED CODE -->` comment in `_includes/waitlist.html` with your Mailchimp embedded form code, and remove the fallback static form below it.
