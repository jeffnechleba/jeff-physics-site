# CosmicPhysics.org — GitHub Pages Starter

This bundle is ready to upload to a new GitHub repository and publish at **https://cosmicphysics.org**.

## What’s inside
- `index.html` — your retro tutoring site (with Calendly popup + floating badge)
- `bigideas.html` — a matching page for your future blog/strategies/solved problems
- `CNAME` — pre-set to `cosmicphysics.org` so GitHub knows your custom domain
- `README.md` — these instructions

---

## Step 1 — Create the repo & upload
1. Create a new public repo on GitHub (e.g., `cosmicphysics-site`).
2. Upload the four files from this folder (`index.html`, `bigideas.html`, `CNAME`, `README.md`).
3. Commit the changes.

## Step 2 — Enable GitHub Pages
1. Repo → **Settings** → **Pages**.
2. Source: **Deploy from branch** → Branch: **main** → Folder: **/** (root). Save.
3. Custom domain: type **cosmicphysics.org** and Save (this matches the CNAME file).

> If you prefer `www.cosmicphysics.org`, you can set that in the Pages settings instead.
> Keep only one value in the CNAME file — either `cosmicphysics.org` or `www.cosmicphysics.org`.

## Step 3 — DNS on Namecheap (root + www)
In **Domain List → Manage → Advanced DNS** add the following records:

**A records for root (cosmicphysics.org):**
- `@ → 185.199.108.153`
- `@ → 185.199.109.153`
- `@ → 185.199.110.153`
- `@ → 185.199.111.153`

**CNAME for www:**
- `www → <yourusername>.github.io`

Save. Propagation usually takes 15–60 minutes.

## Step 4 — Enforce HTTPS
Once GitHub detects DNS, in **Settings → Pages** check **Enforce HTTPS**.

## Step 5 — Test
Visit `https://cosmicphysics.org` and `https://www.cosmicphysics.org`.
If you see a 404, verify:
- `index.html` is in the repo root
- Pages source is `main` and folder `/`
- `CNAME` contains `cosmicphysics.org`
- Wait a few minutes and refresh

---

## Editing
- Replace email and any copy you want in `index.html` and `bigideas.html`.
- To add more pages, create additional `.html` files and link them in the nav.

Have fun 🚀
