# Ironclad persona cards site

This is a small static site designed to be easy to publish and easy to edit after you get feedback from Ironclad.

## What this package includes
- `index.html` — the full shareable page
- `vercel.json` — simple static hosting settings for Vercel

## Best publishing option
Use **GitHub + Vercel**.

Why this is the best setup:
- Vercel gives you a clean public URL for sharing.[cite:47]
- Vercel automatically redeploys whenever you push an edit to your connected Git repository.[cite:44][cite:47]
- GitHub makes the file easy to edit directly in the browser using the pencil/edit action, then commit changes.[cite:48][cite:54][cite:57]

## Fastest setup

### 1. Create a GitHub repository
Create a new repo, for example:
- `ironclad-persona-cards`

### 2. Upload these files
Upload `index.html`, `vercel.json`, and this `README.md` into the root of that repo.

### 3. Deploy with Vercel
1. Sign in to Vercel.
2. Click **Add New Project**.
3. Import the GitHub repository.
4. Leave the framework preset as **Other** or keep defaults for a static project.[cite:44]
5. Keep the output directory as the project root for a plain static site.[cite:44]
6. Deploy.

Vercel’s standard Git-based deployment flow creates a deployment when code is pushed to a connected repository.[cite:47]

## How to edit later

### Option A: Edit in GitHub browser
This is the simplest way.
1. Open the GitHub repo.
2. Open `index.html`.
3. Click the pencil icon to edit the file in the browser.[cite:54][cite:57]
4. Make your changes.
5. Commit the changes.

Once committed and pushed to the repository, GitHub Pages-style workflows and Vercel-connected repos reflect those edits after deployment updates.[cite:48][cite:54][cite:57]

### Option B: Edit locally on your Mac
1. Clone the repo.
2. Edit `index.html` in Cursor, VS Code, or another editor.
3. Commit and push:

```bash
git add .
git commit -m "Update persona cards"
git push
```

Pushing changes to a connected repository triggers a fresh Vercel deployment automatically.[cite:44][cite:47]

## Important note on previews
For the thumbnail and description preview to render properly in LinkedIn, WhatsApp, and similar apps, share the **public Vercel URL**, not a local file path or private file link. Social platforms generally fetch Open Graph metadata from a live public page.[cite:29][cite:35][cite:38]

## Suggested editing areas
Likely areas you will want to tweak after feedback:
- Headline and subhead
- Persona wording
- Discovery questions
- Commercial consequence lines
- Tag labels
- Description metadata near the top of `index.html`

## Optional next step
If you want a cleaner branded URL later, connect a custom domain in Vercel after the first deployment.
