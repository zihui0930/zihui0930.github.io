# Zihui Zhang - Personal Homepage

This folder contains a static personal homepage suitable for GitHub Pages.

## Files

- `index.html`: main page content
- `assets/css/style.css`: page styling
- `assets/docs/CV_Zihui_Zhang.pdf`: downloadable CV
- `assets/images/`: image placeholders (you can add your own photos here)
- `.nojekyll`: disables Jekyll processing on GitHub Pages

## Local preview

```bash
cd /home/zihui/SSD/Wan2.1/homepage
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

### Option A: User site (recommended)
1. Create a GitHub repository named `<your-github-username>.github.io`.
2. Copy all files from this folder to that repository root.
3. Commit and push to `main`.
4. Open `https://<your-github-username>.github.io`.

### Option B: Project site
1. Create a repository, e.g. `homepage`.
2. Push this folder content to repository root.
3. In GitHub repo settings, open **Pages**.
4. Set source branch to `main` and folder to `/ (root)`.
5. Visit `https://<your-github-username>.github.io/<repo-name>/`.

## Update content quickly

Edit the sections in `index.html`:
- About
- Research Interests
- Education
- Selected Publications
- Academic Activities

Replace the CV file at `assets/docs/CV_Zihui_Zhang.pdf` when you update your resume.

## Image placeholders

The page already reserves empty image positions. You only need to drop files into these paths:

- `assets/images/avatar.jpg` (recommended `512x512`)
- `assets/images/research-overview.jpg` (recommended `1600x900`)
- `assets/images/project-showcase.jpg` (recommended `1600x900`)

