# Anshida Ayoob — Product Design Portfolio

This folder contains the complete, production-ready website ready for GitHub Pages hosting.

## File Structure
- `index.html`: The latest portfolio codebase (v30)
- `avatar.jpg`: Hero profile image
- `resume.pdf`: Downloadable resume
- `oracle-thumb.jpg`, `subtitles-thumb.jpg`: Project cards thumbnails
- `oracle-agentic-app.png`, `oracle-data-collection.png`, `analytics.png`, `Data Workbench.png`: Focus area visuals
- `sidequests/`: The 14 active sidequest images
- `.nojekyll`: Ensures GitHub Pages serves all assets directly without Jekyll processing

---

## How to Host on GitHub Pages

### Option A: Via GitHub Web Interface (Simplest)
1. Go to [GitHub](https://github.com) and click **New repository**.
2. Name it either:
   - `<your-username>.github.io` (for a clean root URL like `https://anshidaayoob.github.io`)
   - OR `portfolio` (for `https://anshidaayoob.github.io/portfolio`)
3. Choose **Public**, leave other checkboxes unchecked, and click **Create repository**.
4. In the repository page, click **uploading an existing file**.
5. Drag and drop all files and the `sidequests` folder from inside this `portfolio` directory into GitHub.
6. Commit the changes.
7. Go to **Settings** → **Pages**:
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)`, then click **Save**.
8. Within 1-2 minutes, your website will be live!

---

### Option B: Via Terminal / Git CLI
Open Terminal, navigate to this folder, and run:

```bash
cd portfolio
git init
git add .
git commit -m "Deploy Anshida's portfolio to GitHub Pages"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```
Then go to **Settings** → **Pages** on GitHub and set Source to `main` branch.
