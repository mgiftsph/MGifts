# MGifts — Corporate Gifting & Custom Giveaways

## Landing Page

Professional landing page for MGifts corporate gifting business in the Philippines.

- **Live Site:** `index.html`
- **Form Backend:** Google Sheets + Apps Script (no third-party services)
- **Design:** Navy/Gold color scheme, Playfair Display + Quicksand fonts

## Project Structure

```
.
├── index.html                          # Main landing page (deploy this)
├── README.md                           # This file
├── docs/
│   ├── SETUP_GOOGLE_APPS_SCRIPT.md    # Apps Script setup guide
│   └── GoogleAppsScript_FormHandler.js # Apps Script code
└── assets/                             # Future: images, styles
```

## Form Submission Flow

1. User fills out contact form on landing page
2. Form data submitted via fetch to Google Apps Script
3. Apps Script writes data to Google Sheet
4. User sees success confirmation

**Google Apps Script URL (hardcoded in index.html):**
```
https://script.google.com/macros/s/AKfycbz3XmLFfkfNR8xLXwQOmKx1uG-KIQWSzXN7EFcAghLJmslntVmVLKqGYQMyE2_Tu_bQ/exec
```

## Deployment

### Option 1: GitHub Pages (Free)
1. Push to GitHub
2. Enable GitHub Pages in repo settings
3. Page will be live at: `https://yourusername.github.io/mgifts`

### Option 2: Custom Domain
1. Deploy to any web server (Vercel, Netlify, your own host)
2. Point domain to the deployment

## Updates & Changes

To update the landing page:
1. Edit `index.html` locally
2. Commit and push to GitHub
3. Changes deploy automatically (if using GitHub Pages)

## Contact Form Integration

The contact form submits to a Google Apps Script that writes submissions to a Google Sheet:
- **Sheet Name:** MGifts Contact Form Submissions
- **Columns:** Timestamp, Name, Email, Company, Message, Status

See `docs/SETUP_GOOGLE_APPS_SCRIPT.md` for detailed setup instructions.

---

**Founder:** Gigi Borbon & Mercia  
**Business:** Corporate Gifting & Custom Giveaways  
**Service Areas:** Metro Manila, Iloilo, Western Visayas (Philippines)