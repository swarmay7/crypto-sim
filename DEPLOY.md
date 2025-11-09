Deploy instructions (quick):
1. Create a new repository on GitHub (public), e.g., `crypto-simulator`.
2. Upload all files from this folder (or push via git) to the repository root.
3. Make sure default branch is `main` and push.
4. On push the workflow will run and publish the site to GitHub Pages.
5. The site URL will be: https://<your-username>.github.io/<repo-name>/

Git (example):
  git init
  git add .
  git commit -m "Initial commit — cleaned simulator"
  git branch -M main
  git remote add origin https://github.com/<your-username>/<repo-name>.git
  git push -u origin main
