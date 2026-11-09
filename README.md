# Proserva Conference Pages

Standalone marketing assets for Proserva's MASA (Minnesota) conference outreach.

| File | What it is |
|---|---|
| `proserva-masa.html` | Standalone copy of the redesigned MASA landing page. Opens by double-click; images are embedded, the Wistia video needs an internet connection. |
| `proserva-masa-email.html` | Short HTML email for MASA, built from the MASA landing page content. Table-based layout with inline styles for Gmail, Outlook and Apple Mail. |
| `assets/proserva-logo.png` | Proserva logo used by the email. |
| `assets/masa-email-dashboard.jpg` | Product screenshot used in the email hero. |

## Preview

- MASA landing page: https://htmlpreview.github.io/?https://github.com/isissi/landing-page/blob/main/proserva-masa.html
- MASA email: https://htmlpreview.github.io/?https://github.com/isissi/landing-page/blob/main/proserva-masa-email.html

## Before sending the email

Replace these placeholders with your email platform's merge tags or real links:

- `{{FIRST_NAME}}` (set a fallback such as "there")
- `{{BOOKING_URL}}`
- `{{VIEW_IN_BROWSER_URL}}`
- `{{UNSUBSCRIBE_URL}}`
- `{{COMPANY_POSTAL_ADDRESS}}`

Suggested subject line: **15 minutes at MASA could save your team 1,000+ hours**

The logo and screenshot load from `https://raw.githubusercontent.com/isissi/landing-page/main/assets/`, which only works while this repository is public. For production, upload both files in `assets/` to your email platform and swap the `src` URLs.
