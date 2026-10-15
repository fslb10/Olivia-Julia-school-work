# Biodiversity Explorer 🌿

An interactive **Grade 6 Science** biodiversity review based on two class worksheets.

## Open the quiz

Open `index.html` in any modern browser. The app is one HTML file with inline styling and JavaScript; no build, server, account, or external libraries are required.

## Inside the quiz

- **7 vocabulary multiple-choice** questions: habitat, community, species, organism, biodiversity, latitudinal biodiversity gradient, classification system.
- **5 written answers** naming the five kingdoms: Monera, Protists, Fungi, Plants, Animals. Order and capitalization do not matter, and repeated names do not count twice.
- **5 matching questions** using three characteristics for each kingdom.
- **5 matching questions** for vertebrates: mammals, birds, reptiles, fish and amphibians.
- **5 matching questions** for invertebrates: mollusks, crustaceans, worms, insects and arthropods.
- **15 final questions** mixing multiple choice, true/false and fill-in-the-blank.

**42 points total.**

Choose **Practice Mode** for explanations after each section or **Test Mode** to see scoring only when finished. Responses are saved to the device's browser localStorage. Results can be printed. No learner information is transmitted anywhere.

The quiz follows the traditional classroom *five-kingdom* model. It corrects a few common misconceptions, such as reptiles being cold-blooded and arthropods not all having eight legs.

## Publishing on GitHub Pages

The deploy workflow at `.github/workflows/pages.yml` publishes the quiz automatically after GitHub Pages is enabled. Its initial run failed with "Get Pages site failed: Not Found" because Pages is **not yet enabled**.

1. Visit **Settings → Pages** for this repository.
2. Under **Build and deployment**, set **Source → GitHub Actions** (not "Deploy from a branch").
3. If GitHub cannot enable Pages for this private repository under the owner's plan, GitHub Pages requires the repository to be public on GitHub Free. **Do not change its visibility without the owner's approval.** Paid plans may allow Pages from a private repository.
4. From the **Actions** tab, open **Deploy Biodiversity Explorer to GitHub Pages** and rerun the workflow (or commit a small change to `index.html` or workflow).
5. Confirm that the job is green and the **Pages** settings page provides a live **Visit site** link.

Expected default live address, **only when the deployment succeeds**:
`https://fslb10.github.io/Olivia-Julia-school-work/`

Only `index.html` is uploaded as the public website. The source repository remains private unless deliberately changed.

## Editing

All questions and answers are stored in the `BANK` array at the beginning of the inline script in `index.html`. Each matching group and written answer has a specific answer key, and the scoring functions handle answer validation and feedback.
