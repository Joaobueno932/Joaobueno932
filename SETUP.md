# Installation

1. On GitHub, create a **public** repository with the exact name `Joaobueno932` under your account `Joaobueno932`.
2. Copy `README.md` to the repository root.
3. Copy `.github/workflows/snake.yml` into the same path in that repository (keep the hidden `.github` directory).
4. In **Settings → Actions → General → Workflow permissions**, enable **Read and write permissions** if needed for the workflow to push its generated files.
5. In **Actions → Update contribution snake → Run workflow**, execute the workflow once.
6. Verify the `output` branch contains the two SVG files. Subsequent daily runs update them automatically.

The stats cards rely on third-party services and can occasionally be rate-limited or unavailable. Contributions in private repositories may not appear in third-party visualizations unless the service supports private contributions and is authorized to access them. The profile does not reveal proprietary project code.
