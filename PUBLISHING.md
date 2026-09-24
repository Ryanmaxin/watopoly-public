# Publishing the Watopoly page

This folder is the public site. It contains the page, gameplay screenshot, and
shareable design documents. The course assignment PDF is reference material only;
`.gitignore` excludes it from the public repository.

To publish for the first time:

1. Push this folder to `Ryanmaxin/watopoly-public` on the `main` branch.
2. In the GitHub repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
3. The page will be at <https://ryanmaxin.github.io/watopoly-public/> after GitHub finishes publishing.

Each later push to `main` republishes the page and linked documents. No custom
GitHub Actions workflow is needed for this static site.
