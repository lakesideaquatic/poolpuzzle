# Pool Puzzle Generator

A single-page tool that builds a week of pool puzzles (Monday–Saturday lane schedules) for a swim club.

Enter each group's size, practice length, days per week and time window, add any other pool operations (high school practice, water polo, lessons), and the generator lays out every day's lanes. Blocks can then be arranged by hand, printed, or exported to Excel / Google Sheets.

## Using it

Open the site link, or download `index.html` and open it in any browser. Nothing is installed and nothing is sent anywhere: the whole tool runs in the browser.

- **Export setup / Import setup** saves your groups and pool settings to a file and loads them back. The page does not remember your setup on its own, so export before closing.
- **Print / PDF** gives a week-at-a-glance page plus one landscape page per day.
- **Export Excel / Sheets** downloads a formatted `.xlsx` workbook.

## Hosting on GitHub Pages

1. Upload `index.html` and `README.md` to a public repository.
2. In the repository, go to **Settings → Pages**.
3. Set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<username>.github.io/<repository>/`.

To update the site, upload a new `index.html` over the old one.
