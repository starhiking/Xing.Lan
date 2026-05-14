# Xing Lan Academic Homepage

This is a static academic homepage that can be deployed directly with GitHub Pages. The entry file is `index.html`.

## Local Preview

Open `index.html` directly in a browser, or run the following command in the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repository. For a user homepage, name it `your-username.github.io`.
2. Commit and push this directory to the repository's `main` branch.
3. If the repository is not named `your-username.github.io`, open `Settings -> Pages`, select `Deploy from a branch`, choose the `main` branch, and set the folder to `/root`.
4. Wait for GitHub Pages to finish building, then open the published URL.

## Update Content

- Portrait: replace `assets/profile.png`.
- Bio, publications, admissions, and contact information: edit `index.html`.
- Visual style: edit `styles.css`.
