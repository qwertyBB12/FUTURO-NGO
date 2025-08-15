
# Futuro.ngo — Netlify Starter (with Visual CMS)

This folder is ready to deploy **today** and includes a visual editor at `/admin`.

## Quick Launch (10–15 min)
1. Create a **new GitHub repo** and upload these files (or drag-drop the ZIP contents).
2. Go to **Netlify → Add new site → Import from Git** → select the repo.
3. Build settings: **Base directory** empty, **Build command** none, **Publish directory** `/`.
4. After deploy, go to **Netlify → Identity** → Enable → Invite yourself (and team) via email.
5. In **Identity → Services**, enable **Git Gateway**.
6. Visit `https://YOUR-SITE.netlify.app/admin` and log in with the invite. You can now edit:
   - **Projects** → creates JSON files in `assets/projects/`
   - **Settings** → updates `assets/settings.json`
   - (Advanced) **Homepage (HTML)** raw editing

## Projects
- The homepage loads projects from `assets/projects.json` (for initial sample data) *and* from any JSON files you create under `assets/projects/` via the CMS.
- To consolidate, you can delete `assets/projects.json` later and only use the CMS collection.

## Kajabi Integration
- Replace `apply_url` in **Settings** with your real Kajabi checkout/application link.
- You can reference Kajabi-hosted images/videos directly in the editor.

## Custom Domain
- In Netlify: **Domain settings** → add `futuro.ngo` and follow the DNS prompts.

