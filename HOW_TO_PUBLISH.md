# Publish this site with GitHub Pages

No command line is required.

1. Sign in to GitHub and create a new repository named exactly `YOURUSERNAME.github.io`, replacing `YOURUSERNAME` with your GitHub username. Make it **Public**. Adding a README is fine.
2. Open the repository. Choose **Add file → Upload files** and upload the contents of this website folder (`index.html`, `research.html`, `style.css`, `cv.pdf`, and optionally `.nojekyll` and the documentation files). Do not upload the outer folder as a single folder.
3. At the bottom, enter a commit message such as `Initial personal website` and commit the files to the `main` branch.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select branch `main` and folder `/(root)`, and save.
5. Visit `https://YOURUSERNAME.github.io/`. It can take several minutes for the first deployment to appear.

## Updating it later

For a tiny personal site, it is perfectly reasonable to edit a file on GitHub and commit directly to `main`. A commit is a recorded snapshot of your changes, so the history remains available.

For a safer workflow, create a branch such as `update-research`, make and commit your edits there, then open a pull request proposing to merge that branch into `main`. Review the displayed differences, merge the pull request, and GitHub Pages will publish the updated `main` branch.

## Git vocabulary in one minute

- **Repository**: the project folder plus its complete version history.
- **Commit**: a named snapshot of changes.
- **Branch**: a parallel line of work; `main` is normally the public/current version.
- **Pull request**: a proposal to merge one branch into another, with a page showing the differences and allowing review or discussion.
- **Merge**: accepting those changes into the target branch.

For this website you do not need pull requests for every tiny edit; they are useful when you want to experiment without changing the live `main` version immediately.
