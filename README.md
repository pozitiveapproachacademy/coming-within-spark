# Coming Within℠

Static Sovereign Spark℠ Practice page for deployment to Vercel.

## File Structure

```text
COMING WITHIN MINI/
├── index.html
├── README.md
└── assets/
    └── coming-within-hero.png
```

## Static Site Notes

- No login.
- No database.
- No user accounts.
- No stored personal responses.
- Worksheet actions run locally in the browser only.
- The local image asset is referenced with a relative path: `assets/coming-within-hero.png`.
- HeyGen lesson videos are embedded from their hosted URLs.
- No build command or install command is required.

## Deploy With GitHub + Vercel

1. Create a new GitHub repository.
2. Add `index.html`, `README.md`, and the `assets/` folder to the repository.
3. Commit and push the files to GitHub.
4. In Vercel, choose **Add New Project**.
5. Import the GitHub repository.
6. Leave framework/build settings as the static defaults:
   - Framework Preset: `Other`
   - Build Command: leave empty
   - Output Directory: leave empty
   - Install Command: leave empty
7. Deploy.

Vercel will serve `index.html` from the project root.
