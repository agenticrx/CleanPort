# Deploy BuildRadar

## GitHub Pages

1. Open the repository Settings → Pages.
2. Under **Build and deployment**, choose **GitHub Actions**.
3. Push to `main` (already configured).
4. The workflow in `.github/workflows/deploy.yml` publishes the site.
5. The resulting site will use the repository GitHub Pages URL.

## Product validation

The MVP is intentionally static so the first test can happen before paying for infrastructure.

### First customer test

- Recruit 10 local specialty contractors.
- Ask each for 2–3 trades and preferred service radius.
- Send 3–5 matched projects per contractor.
- Track whether they ask for a contact, bid package, introduction, or more projects.
- Charge only after a contractor confirms the data is useful.

### Next engineering milestone

Move `data/projects.json` to a real database and add project ingestion + verification. Keep the frontend contract stable so the data layer can change without redesigning the product.
