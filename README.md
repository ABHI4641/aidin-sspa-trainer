# Aidin 200 W SSPA – Operator Trainer

Static site: `index.html` (everything inlined, no build step) + `vercel.json`.

## Deploy (CLI, ~1 min)
    npm i -g vercel
    cd aidin-sspa-trainer
    vercel            # first run: log in, accept defaults (Framework: Other, no build command)
    vercel --prod     # production URL

## Deploy (GitHub)
Push this folder to a repo → vercel.com/new → Import → Framework preset "Other" → Deploy.

The site is set to noindex (not listed on Google) since it carries Aidin branding.
Remove the robots meta tag and the X-Robots-Tag header once Aidin approves a public launch.
