# Cortland Community Visit Guide

A mobile-first, interactive guide for new associates in Cortland's Centers of Excellence (COE) — The Leasing Hub, Screening and Applications (SAS), and Resident Services (RS) — used during the first-Friday community visit in new-hire training.

## Publish with GitHub Pages

1. Create a repository and upload `index.html` (and this README) to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute, your link appears at the top of the Pages settings: `https://<your-org>.github.io/<repo-name>/`

Share that link with associates. It opens directly on their phones.

## How it works

- **Single file.** All styles, scripts, and the Cortland logo are embedded in `index.html`. No build step.
- **External resources:** Google Fonts (Outfit, Josefin Slab) and jsPDF from cdnjs for the "Save as PDF" button. If either fails to load, the page still works with system fonts; associates can use "Copy my takeaways" instead of PDF.
- **Privacy.** Notes and takeaways are saved only in the associate's own browser (localStorage). Nothing is sent or stored on a server. "Start a fresh visit" clears everything.
- **Accessibility.** Keyboard operable, large touch targets, no hover-only interactions, respects reduced-motion and dark-mode settings.

## Editing content

All content lives in the `CONTENT` section near the top of the `<script>` block: `COES`, `STOPS`, `AREAS`, `CULTURE_PROMPTS`, `VALUES`, `SHARED_Q`, `LENS_Q`, `STAGES`, and `TAKE_PROMPTS`. Edit the text there and re-upload.

## Sources

Content is based on the Cortland Brand Guidelines v2.2, the COE brand sheets, and SME-approved descriptions and stage mappings. Department names are preserved exactly as approved.

> Internal use. The repository can be private if your GitHub plan supports private Pages; otherwise anyone with the link can view the page. The page contains no confidential data, and `noindex` asks search engines not to list it.
