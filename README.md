# Portfolio — Kush Mehta

Personal portfolio site. Static HTML/CSS, no build step, no dependencies.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | Homepage — hero, about, project hub, skills, research, contact |
| `projects-aerial.html` | Aerial robotics & Team Arrow competition aircraft |
| `projects-embedded.html` | Embedded systems, cryptography, FPGA, gem5 |
| `projects-data.html` | Data science, computer vision, machine learning |
| `style.css` | Shared styles — nav, buttons, tags, footer, tokens |
| `Kush_Mehta_Resume.pdf` | One-page résumé (linked from hero + contact) |
| `Kush_Mehta_CV.pdf` | Full CV (linked from contact) |
| `google757a6a32f4b19323.html` | Google Search Console verification |

Each project page carries its own page-specific CSS in a `<style>` block; anything
shared across pages belongs in `style.css`.

## Running locally

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
```

## Updating the résumé / CV

The PDFs in this folder are copies. The originals live in `../../Resume-CV/Current/`.
After editing an original, copy it back over the one here so the download links stay current.

## Outstanding TODOs

Search the source for `TODO:` — currently:

- SAE Aero Design East 2026 result badge in `projects-aerial.html`.
- SAE DDC Micro 2026 has no project entry yet.
- Preprint link for the jamming-utilization paper (`index.html`, Research & IP).
- Patent application number / filing date / jurisdiction (`index.html`, Research & IP).
- Whether the ISRO internship report can be published publicly (`projects-embedded.html`).
- Eight "Report (Coming Soon)" buttons across the project pages still point at `#`.
