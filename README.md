# Proserva Conference Pages

Standalone marketing assets for Proserva's MASA (Minnesota) conference outreach.

| File | What it is |
|---|---|
| `proserva-masa.html` | Standalone copy of the redesigned MASA landing page. Opens by double-click; images are embedded, the Wistia video needs an internet connection. |
| `proserva-masa-email.html` | Short HTML email for MASA, built from the MASA landing page content. Table-based layout with inline styles for Gmail, Outlook and Apple Mail. |
| `assets/proserva-logo.png` | Proserva logo used by the email. |

## Preview

- MASA landing page: https://htmlpreview.github.io/?https://github.com/isissi/landing-page/blob/main/proserva-masa.html
- MASA email: https://htmlpreview.github.io/?https://github.com/isissi/landing-page/blob/main/proserva-masa-email.html

## Before sending the email

Replace these placeholders with your email platform's merge tags or real links:

- `{{BOOKING_URL}}`
- `{{VIEW_IN_BROWSER_URL}}`
- `{{UNSUBSCRIBE_URL}}`
- `{{COMPANY_POSTAL_ADDRESS}}`

The logo loads from `https://raw.githubusercontent.com/isissi/landing-page/main/assets/proserva-logo.png`, which only works while this repository is public. For production, upload `assets/proserva-logo.png` to your email platform and swap the two `src` URLs.
