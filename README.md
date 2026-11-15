# TechCypher — personal portfolio

A responsive, static personal website built with HTML, CSS and a little JavaScript. It is ready to deploy to Cloudflare Pages at no hosting cost.

## Preview locally
Open `index.html` in your browser. No build step or package installation is required.

## Before publishing
Search `index.html` for `Gokul` and replace it if needed. Also update:
- `hello@example.com` with your real public contact email
- GitHub and LinkedIn links with your profile URLs
- About text, project descriptions, skills and location to reflect your real details

The project cards are starter placeholders. Replace them with real projects as you complete them. Avoid publishing private contact details.

## Deploy to Cloudflare Pages (free)
1. Create or sign in to a Cloudflare account: https://dash.cloudflare.com/
2. Put this folder in a GitHub repository (for example, `techcypher-site`).
3. In Cloudflare, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
4. Select your repository.
5. For a plain HTML site, leave the framework preset as **None**. Leave the build command empty and set the build output directory to `/` (or the repository root, depending on the setup screen).
6. Deploy. Cloudflare gives you a `*.pages.dev` address.

## Connect a custom domain
In your Pages project, open **Custom domains** and add the domain you have registered. Follow the DNS instructions Cloudflare displays. A free Pages deployment does not make a separately registered custom domain free.

## Notes
- No backend, database, or server-side code is used.
- Google Fonts are loaded externally; the site still works with system fonts if they are unavailable.
- `_headers` adds a few basic security headers.
