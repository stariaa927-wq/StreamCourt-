# StreamScout — Vercel-ready static site

This is a self-contained static website. No build step, database, server, or environment variables are required.

## Deploy
1. Sign in to Vercel.
2. Choose **Add New → Project** and import a Git repository containing these files, or use the Vercel CLI from this folder.
3. For a static site, leave Framework Preset as **Other**, with no build command and no output directory (the `index.html` is at the root).
4. Deploy.

The site fetches live TV catalogue data from TVmaze in the visitor's browser. It shows provider homepages as navigation shortcuts; it does not claim that a particular title is available on those providers.
