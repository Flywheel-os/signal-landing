# Signal by Flywheel: landing page

Static landing page for Signal, served at https://signal.flywheelos.com via GitHub Pages.

- Everything lives in `index.html` (no build step). Push to `main` and Pages redeploys.
- `CNAME` sets the custom domain. DNS: `signal` CNAME to `flywheel-os.github.io` in GoDaddy.

## Before launch

- [ ] Replace placeholder testimonials, customer logos and pricing
- [ ] Wire up CTA links (Request demo, Try Signal, Talk to sales)
- [ ] Confirm which networks support replies (copy currently treats RSS feeds as listen-only)
- [ ] Remove the `noindex` meta tag in `index.html`
