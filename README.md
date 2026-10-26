# Prawin Gandhi D — AI Developer Portfolio

A responsive personal portfolio website showcasing Generative AI, LangGraph, FastAPI, and Machine Learning projects.

## Live Demo & Hosting

This site is built as a fast, dependency-free static web application and is ready to deploy on any static hosting provider.

### Option 1: GitHub Pages (Recommended)
1. Push your repository to GitHub:
   ```bash
   git add .
   git commit -m "Configure hosting components and gitignore"
   git push origin main
   ```
2. In your GitHub repository, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
4. Select `main` branch and `/ (root)` folder, then click **Save**.
5. Your site will be published at `https://<username>.github.io/<repo>/`.

### Option 2: Vercel
1. Import this repository into [Vercel](https://vercel.com).
2. Framework Preset: **Other** / Static.
3. Root Directory: `./`
4. The included `vercel.json` will automatically configure clean URLs and HTTP security headers.

### Option 3: Netlify
1. Connect this repository to [Netlify](https://netlify.com).
2. Build command: *(leave empty)*
3. Publish directory: `.`
4. The included `_headers` file provides security headers out of the box.

---

## Project Structure

```text
├── index.html        # Main portfolio webpage with SEO & OG tags
├── 404.html          # Fallback error page for static hosts
├── robots.txt        # Search engine crawler instructions
├── sitemap.xml       # SEO sitemap
├── vercel.json       # Vercel hosting rules and security headers
├── _headers          # Netlify security headers configuration
├── .gitignore        # Clean Git repository ignore patterns
└── README.md         # Deployment and project overview
```
