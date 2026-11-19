# S. M. Abdul Hamid — Academic Portfolio (Vercel-ready)

Single-file static site. Everything (HTML, CSS, JS) is in `index.html`.
No build step, no framework, no dependencies to install.

## Deploy — Option A: Vercel CLI (fastest)
1. Install Node.js, then in this folder run:
   npm i -g vercel
   vercel
2. Follow the prompts (link to your Vercel account, accept defaults).
3. Your live URL is shown when it finishes.

## Deploy — Option B: GitHub + Vercel dashboard
1. Create a new GitHub repo, upload `index.html` (and optionally `vercel.json`) to it.
2. Go to vercel.com/new, Import that repo.
3. Framework Preset: Other. Build Command: leave empty. Output Directory: leave empty.
4. Deploy.

## Deploy — Option C: Drag the folder
If you use the Vercel CLI, you can also run `vercel --prod` from this folder for a production deploy.

## Edit later
Edit `index.html` directly, then redeploy with `vercel --prod` (CLI) or push to GitHub (dashboard auto-deploys).
