# RiseRep Alarm - Account and Data Deletion Page

This repository contains a static GitHub Pages site for the RiseRep Alarm account and data deletion URL required by Google Play.

## Files

- `index.html`: Account and data deletion page
- `.nojekyll`: Prevents Jekyll processing on GitHub Pages

## Recommended repository name

Use one of the following:

- `riserep-account-deletion`
- `riserep-alarm-support`
- `yottun114514-afk.github.io` if you want this to be your main GitHub Pages site

For a project site named `riserep-account-deletion`, the final URL will usually be:

```text
https://yottun114514-afk.github.io/riserep-account-deletion/
```

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `.nojekyll`.
3. Open the repository on GitHub.
4. Go to **Settings**.
5. Go to **Pages**.
6. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. Click **Save**.
8. After a short while, GitHub Pages will show the public URL.

## URL to enter in Google Play Console

Once published, paste the GitHub Pages URL into:

```text
Play Console
→ App content
→ Data safety
→ Account deletion URL
```

Make sure the URL opens without login.
