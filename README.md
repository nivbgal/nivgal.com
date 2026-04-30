# nivgal.com

Standalone static site for GitHub Pages.

## What is here

- `index.html` - the main personal hub and resume page.
- `resume/index.html` - a clean `/resume/` route that redirects to the resume section.
- `assets/nivgal-consultations-logo.png` - local logo asset used in the header.
- `assets/profile.jpg` - profile photo used in the hero card.
- `assets/second-screen-demo.mp4` - demo video opened from the second-screen sports and Lieferando experience references.
- `CNAME` - custom domain file for `nivgal.com`.
- `.nojekyll` - tells GitHub Pages to serve the static files directly.
- `404.html` - lightweight fallback page for unknown routes.

## Publish on GitHub Pages

The live repository is `nivbgal/nivgal.com`.

GitHub Pages is configured to publish from:

- Branch: `main`
- Folder: `/`
- Custom domain: `nivgal.com`

## DNS Records

At the DNS provider for `nivgal.com`, add these records.

For the apex/root domain:

| Type | Name | Value |
| --- | --- | --- |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |

For `www`:

| Type | Name | Value |
| --- | --- | --- |
| CNAME | `www` | `nivbgal.github.io` |

After DNS propagates, return to GitHub Pages settings and enable HTTPS if GitHub has not enabled it automatically yet.

## Profile Photo

The profile card uses `assets/profile.jpg` and falls back to the `NG` portrait tile if the file is missing.
