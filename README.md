# TaskFlow AI — Static Demo Site

This repository contains a simple static demo site for TaskFlow AI.

Preview locally

```bash
cd /workspaces/TaskFlowAI-
# With Python 3
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

GitHub Pages (automatic deploy)

A GitHub Actions workflow is included to publish the repository contents to GitHub Pages whenever you push to `main`.

- Ensure the repository is hosted on GitHub and `main` is the default branch.
- After pushing, check the Actions tab for the `Deploy to GitHub Pages` workflow.
- In the repository Settings → Pages, set the source to `gh-pages` branch (if not auto-configured).

Next steps

- Want a custom domain? I can add a `CNAME` file and update the workflow.
- Want the CSS split out, more accessibility improvements, or a small contact form? I can add that next.

---

Generated/updated by GitHub Copilot assistant.