# Shelley Broda — Personal Portfolio

A personal portfolio presenting my Tulane education, legal experience, brand communication work, and campus leadership. Created with OpenAI Codex for my AI Tools website assignment.

## How the site works

- `index.html` contains the portfolio’s content and meaningful HTML structure.
- `resume.html` is the complete résumé, with a print-friendly layout. A visitor can use Print → Save as PDF.
- `styles.css` controls colors, typography, spacing, and layouts for different screen sizes.
- `.nojekyll` tells GitHub Pages to serve these static files directly.

The site works without JavaScript, a build step, an account, or third-party font downloads. Navigation links jump to sections using their `id` attributes. Contact links use `mailto:` to open the visitor’s email application. The site itself does not send messages or collect form submissions.

## GitHub in plain English

Git tracks changes to files. A commit is a saved snapshot with a description of what changed. A repository holds the files and their history. GitHub hosts that repository so work can be shared, reviewed, and restored. GitHub Pages publishes the website files at a public web address.

The repository URL shows the code; the Pages URL shows the finished website. Updating the same repository preserves both the history and the stable site address for the second grading round.

## Preview and publish

Open `index.html` directly, or serve this folder with `python3 -m http.server 4173` and visit the address printed by Python. No dependency installation is needed.

For GitHub Pages, keep these files at the repository root. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. Check the deployment status and the published site before submitting its URL.

## Design and accessibility

The design uses navy, blue, serif display type, and clear section divisions. The portfolio prioritizes selected experience; the résumé holds the complete history. Responsive CSS reorganizes columns for narrower screens. Semantic headings, a skip link, visible keyboard focus, and reduced-motion support help visitors navigate the content.

Content is grounded in my résumé rather than invented achievements or performance metrics. No testimonials or client endorsements are implied.

## AI workflow

OpenAI Codex researched portfolio examples and GitHub documentation, adapted my résumé into first-person website copy, wrote the HTML/CSS, and prepared the site for review. The decisions and checks are documented in `PROCESS.md`.

## References

- [GitHub: What is GitHub?](https://docs.github.com/en/get-started/start-your-journey/what-is-github)
- [GitHub: Creating a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [W3C: Developing for web accessibility](https://www.w3.org/WAI/tips/developing/)
- [Brittany Chiang’s portfolio](https://brittanychiang.com/), studied for experience hierarchy and direct navigation.
- [Josh W. Comeau’s website](https://www.joshwcomeau.com/), studied for clear voice and readable presentation of work.

These examples informed the approach; this site’s design and content were authored for my own portfolio.
