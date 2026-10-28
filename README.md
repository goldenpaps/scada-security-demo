# SCADA Security Lab — GitHub Pages

This is a browser-only educational simulation.

## Run locally
Open `index.html` in a browser. No Python packages are required.

## Publish
1. Create a GitHub repository, such as `scada-security-demo`.
2. Upload `index.html` to the repository root and commit to `main`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Open the URL GitHub Pages displays after deployment.

## Existing Python files
You may keep `AWESOME_DEMO_v1.02.py`, `evil.py`, and your secured Python version in the repository for readers to inspect/download. The HTML does not execute Python, connect to port 21000, or use your SQLite database. GitHub Pages is static hosting and cannot run the Tkinter GUI or Python TCP server.

Do not publish secrets, authentication tokens, real infrastructure details, or private data.
