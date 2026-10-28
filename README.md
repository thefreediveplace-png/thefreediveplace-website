# The Freedive Place

A mobile-first static website for The Freedive Place in Dahab, Egypt. The site uses the business's existing public photography and verified public contact information; it has no build step or runtime dependencies.

## Preview locally

Open `index.html` in a browser or serve the repository root with a static HTTP server.

## Review preview

The GitHub Pages review site is available at <https://thefreediveplace-png.github.io/thefreediveplace-website/>. The custom domain is intentionally not configured while the redesign is being reviewed. The Wix site and domain DNS are unchanged.

## Deploy with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the repository root on pushes to `main` and can also be run manually. In the repository settings, select **Pages → Build and deployment → GitHub Actions** if Pages is not already configured.

## Reconnect the custom domain after approval

Only after approving the new site and deciding to switch from Wix:

1. In the repository's **Settings → Pages**, set the custom domain to `www.thefreediveplace.com` and wait for GitHub to verify it.
2. Add a root-level `CNAME` file containing `www.thefreediveplace.com`.
3. At the domain's DNS provider, point the `www` CNAME record to `thefreediveplace-png.github.io`. If the apex domain (`thefreediveplace.com`) should also resolve directly, configure the A/AAAA records shown in GitHub's current Pages documentation.
4. Wait for DNS propagation and HTTPS provisioning in Pages settings before changing or removing the existing Wix configuration.

Do not change Wix settings or domain DNS while the new site is under review. Course details and schedules can change, so contact Waleed for current offerings and availability. No course prices are published on this site.