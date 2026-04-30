# nivgal.com

Standalone static site for GitHub Pages.

## What is here

- `index.html` - the main personal hub and resume page.
- `resume/index.html` - a clean `/resume/` route that redirects to the resume section.
- `assets/nivgal-consultations-logo.png` - local logo asset used in the header.
- `assets/profile.jpg` - profile photo used in the hero card.
- `CNAME` - custom domain file for `nivgal.com`.
- `.nojekyll` - tells GitHub Pages to serve the static files directly.
- `404.html` - lightweight fallback page for unknown routes.

## Publish on GitHub Pages

1. Create a new GitHub repository for this folder.
2. Put these files at the repository root.
3. In repository settings, enable GitHub Pages from the default branch root.
4. Set the custom domain to `nivgal.com`.
5. Point your DNS at GitHub Pages and enable HTTPS once GitHub finishes provisioning the certificate.

## Profile Photo

The profile card uses `assets/profile.jpg` and falls back to the `NG` portrait tile if the file is missing.
