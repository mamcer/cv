# CV — Mario Moreno

My CV as code: a single Markdown source with embedded CSS, rendered to PDF.

- **Latest PDF:** [CV_Mario_Moreno.pdf](https://github.com/mamcer/cv/raw/pdf-download/CV_Mario_Moreno.pdf)
- **Source:** [CV_Mario_Moreno.md](./CV_Mario_Moreno.md)

Every push to `main` runs a GitHub Action that renders the Markdown with
headless Chrome ([md-to-pdf](https://github.com/simonhaenisch/md-to-pdf),
options in [`.md-to-pdf.json`](./.md-to-pdf.json)), checks that the result is
a single A4 page, and publishes it to the `pdf-download` branch.

To render locally:

```bash
npx md-to-pdf --config-file .md-to-pdf.json CV_Mario_Moreno.md
```
