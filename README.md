# Valkyria Defense Systems landing page

Static, responsive corporate landing page for GitHub Pages.

## Publish
1. GitHub repository Settings > Pages: Deploy from a branch, main, / (root).
2. In Custom domain, enter `www.valkyriadefensesystems.com`.
3. At GoDaddy add four A records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; CNAME `www` pointing to `alexoxy.github.io`.
4. Enable HTTPS when available. Do not modify Gmail MX, SPF, DKIM or DMARC to set up the website.

## Contact form
The form uses FormSubmit.co as an external provider with destination `portugal@valkyriadefensesystems.com`. FormSubmit will require activation via a confirmation email sent to that mailbox when the first submission is made. Until activated, delivery isn't operational. Test the form after activation. This is a third-party service; assess privacy/data-processing needs before public launch. No server-side form handler is supplied by GitHub Pages. For a strictly first-party route, replace form action with a managed API endpoint. Avoid sending secrets through this form.
