# The Freedive Place

A mobile-first static website for The Freedive Place in Dahab, Egypt. The site uses the business's existing public photography and verified public contact information; it has no build step or runtime dependencies.

## Preview locally

Open `index.html` in a browser or serve the repository root with a static HTTP server.

## Deploy with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the repository root on pushes to `main` and can also be run manually. In the repository settings, select **Pages → Build and deployment → GitHub Actions** if Pages is not already configured.

The `CNAME` file selects `www.thefreediveplace.com`. Before switching the live site, configure the DNS CNAME record for `www` to point to `thefreediveplace-png.github.io`, then wait for DNS and HTTPS provisioning in the Pages settings. Keep the Wix site and its DNS unchanged until you're ready to switch. If you also want the apex domain (`thefreediveplace.com`) to resolve directly, configure its DNS records using GitHub's current Pages documentation.

Course details and schedules can change, so contact Waleed for current offerings and availability. No course prices are published on this site.
