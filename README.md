# Feedback System — HTML/CSS Demo

A tiny website for Git/GitHub practice. Use it to learn:
- Initializing a repo and pushing to GitHub
- Branching and making pull requests
- Reviewing and merging changes

## Project Structure
```
github-demo-site/
├─ index.html
├─ styles.css
└─ README.md
```

## Quick Preview
Open `index.html` in your browser.

## Suggested Git Flow
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<you>/github-demo-site.git
git push -u origin main
```

## Collaboration Exercise
1. Create a branch: `git checkout -b feature/add-footer-links`
2. Edit `index.html` to add helpful links in the footer.
3. Commit & push: `git commit -am "feat: add footer links" && git push -u origin feature/add-footer-links`
4. Open a Pull Request on GitHub and request a review.
