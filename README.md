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

## Publishing this repo on GitHub Pages

This repository was **private** when the quiz was uploaded. GitHub Pages supports public repositories on GitHub Free; hosting from private repositories generally requires a paid eligible GitHub plan.

If publishing a public site is acceptable:

1. If your GitHub plan requires it, change the repository visibility to **Public** in **Settings → General → Danger Zone → Change repository visibility**. **Check the repository contains no private materials before doing this.**
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**, then **Save**.
5. Wait for GitHub to finish deploying and open the **Visit site** link on the Pages settings screen.

Expected default address (only after Pages has been activated):
`https://fslb10.github.io/Olivia-Julia-school-work/`

These settings must be selected in GitHub; committing `index.html` alone does not activate Pages.

## Editing

All questions and answers are stored in the `BANK` array at the beginning of the inline script in `index.html`. Each matching group and written answer has a specific answer key, and the scoring functions handle answer validation and feedback.
