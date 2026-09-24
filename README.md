# Applebridge Email Signature Generator

A static internal tool for creating branded Applebridge Family email signatures.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload every file and folder from this package to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the **main** branch and **/(root)** folder, then click **Save**.
6. Allow GitHub a few minutes to publish the site.

The published address will follow this format:

`https://YOUR-ORGANISATION.github.io/REPOSITORY-NAME/`

## Required structure

Keep the following files and folder together:

- `index.html`
- `html2canvas.min.js`
- `assets/`
- `.nojekyll`

The app has no database, build process or server-side requirements.

## Access note

Standard GitHub Pages sites are publicly accessible. Use GitHub Enterprise
Pages or another access-controlled hosting service if the generator must remain
private to the organisation.
