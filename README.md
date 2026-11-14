# Immersive Distribution and Exhibition Toolkit (prototype)

A working prototype of a toolkit that helps artists plan how to distribute and exhibit immersive work (XR, VR, AR, installations and live events) and find the venues, festivals and online platforms that show it.

**Live site:** https://jaceylynn.github.io/Immersive-Distribution-and-Exhibition-Toolkit-Prototype/ (once GitHub Pages is switched on, see below)

## What's in it

- **Planning.** Three guided sections that build a distribution plan:
  - **Vision:** your project, values and goals.
  - **Festivals:** premiere strategy, festival fit and preparation.
  - **Exhibition:** finding venues and platforms, and what to confirm with each host.
- **Your plan.** A summary of your answers that you can download as a PDF, copy as Markdown or send by email.
- **Database.** A filterable map of about 325 venues, festivals, online platforms and support organizations. You can start from a format, a discipline or a part of the world.
- **Resources.** Case studies, catalogues and directories.
- **Glossary.** Plain-language definitions of the terms the toolkit uses.

The toolkit has no accounts and doesn't collect data. Answers stay in the browser and in the page link.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app in one file: code, styles, venue data and images. |
| `wording.txt` | The on-screen wording. Edit this file to change text without touching the code (see below). |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |
| `LICENSE` | MIT License for the code. |
| `LICENSE-CONTENT.md` | CC BY-NC 4.0 license for the toolkit's own written content, and what it doesn't cover. |

## Changing the wording

You can change almost any text on the site by editing `wording.txt` on GitHub. You don't need to install anything.

1. Open **`wording.txt`** in this repository on github.com.
2. Click the **pencil icon** (Edit this file) at the top right of the file.
3. Find the text you want to change. Press Ctrl+F (Cmd+F on a Mac) and type a few words you see on the page.
4. Each line looks like this:

   ```
   What stage is your project in? => What stage is your project in?
   ```

   Change **only the part after `=>`**. Leave the part before `=>` exactly as it is, because that's how the page finds the text.

   ```
   What stage is your project in? => Where is your project at right now?
   ```

5. Click **Commit changes…**, add a short note about what you changed, and click **Commit changes** again.
6. Wait a few minutes, then refresh the live site to see the change.

Some things to keep in mind:

- Keep each entry on one line.
- If the same text appears in more than one place, one edit changes all of them.
- To undo an edit, make the part after `=>` match the part before it again, or use the file's **History** to restore an earlier version.
- Lines that start with `#` are notes and are ignored.
- Some text isn't in the file:
  - Text that includes a changing number, such as "325 matching entries".
  - Venue and festival details, which come from the research team's Airtable data.
  - The case study texts, which quote the IDFA 2025 report word for word.
- If the file is missing or can't be read, the site still works and shows its built-in wording.

## Switching on GitHub Pages

1. Go to the repository's **Settings** and open **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute or two, the site appears at the address shown on that page.

## Data and credits

- **Venue data:** the research team's Airtable base, exported on 8 November 2026. Missing information means "to confirm", not "unsuitable".
- **Case studies:** IDFA DocLab, *Immersive Distribution and Exhibition* report (2025). Images are from the MIT Open Documentary Lab's *XR Distribution Pipelines* page.
- **Fonts:** Fraunces, Red Rose and Space Grotesk from Google Fonts. PDF export uses jsPDF.

## License

- **Code:** MIT License, see `LICENSE`.
- **The toolkit's own written content** (on-screen wording, `wording.txt`, glossary definitions, privacy policy): CC BY-NC 4.0, see `LICENSE-CONTENT.md`.
- **Not covered by either license:** the venue data, the case study texts quoted from the IDFA report, and the case study images from the MIT Open Documentary Lab. They belong to their owners.
