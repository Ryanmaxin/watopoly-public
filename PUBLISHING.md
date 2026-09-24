# Publishing the Watopoly page

This folder is the public site. The Pages workflow publishes only `index.html`,
`styles.css`, `Watopoly.png`, `design.pdf`, and `uml-final.pdf`. The course assignment PDF is kept
locally as reference material and is excluded from Git.

To publish for the first time:

1. Push this folder to `Ryanmaxin/watopoly-public` on the `main` branch.
2. In the GitHub repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Open the **Actions** tab and wait for **Publish Watopoly page** to finish. The page will be at <https://ryanmaxin.github.io/watopoly-public/>.

Each later push to `main` publishes the latest page and the two linked PDFs.
Only put material you are comfortable sharing publicly in this repository.
