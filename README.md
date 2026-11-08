# Portfolio

Published website: https://www.ycwang.me/

This repository contains only the generated website in `site/`. Hugo source files and their editing history are maintained separately.

## Publish an update

1. In the local Hugo source checkout, run `powershell -NoProfile -File .\publish.ps1` (or `deploy.bat`). This rebuilds and replaces only this repository's generated `site/` directory.
2. Review the changes here, commit `site/`, and push to `main`.
3. GitHub Actions uploads `site/` and deploys it to GitHub Pages. You can also run the workflow manually from the Actions tab.

GitHub Pages must use **GitHub Actions** as its publishing source, with **www.ycwang.me** configured as the custom domain.
