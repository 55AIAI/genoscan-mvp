# GenoScan MVP — V1 / V2

Public educational demo for Astana IT University, Technological Entrepreneurship (2026).

- [`/v1/`](./v1/) — before beta feedback (RU/KK).
- [`/v2/`](./v2/) — revised after beta feedback and product-vision update (RU/KK).
- [`/`](./) — bilingual landing page and version selector.

**Important:** Demonstration only. All case records, AMR markers, phenotypic AST results and institutional evidence are fictional. This site must not be used for patient diagnosis, antibiotic selection, or clinical decisions. The 13 questionnaire responses evaluated V1; V2 has not been independently retested.

## Publish on GitHub Pages

1. Create a public repository named `genoscan-mvp` in your GitHub account.
2. Upload all files in this folder **to the repository root**, keeping `v1/index.html` and `v2/index.html`.
3. Go to repository **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, `main`, `/ (root)`, then Save.
4. Once the deployment is active, check `https://USERNAME.github.io/genoscan-mvp/`, plus `/v1/` and `/v2/`.

Alternative: On Windows, with Git and GitHub CLI installed and authenticated, run `./publish.ps1` in PowerShell. The script creates the repository and attempts to turn on Pages; if the Pages API is blocked, follow step 3 above.

## Source artifacts

The standalone source HTML files were copied from `GenoScan_MVP_V1_RU_KK.html` and `GenoScan_MVP_V2_RU_KK.html` without rewriting application behavior. Both are self-contained HTML/CSS/JS without external assets.