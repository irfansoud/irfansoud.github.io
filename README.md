# Irfan Soudagar — academic website

Responsive HTML/CSS/vanilla JavaScript with no build or dependencies. Open index.html directly, or run `python -m http.server 8000` in this folder.

## Editing

- index.html contains all public content and links.
- styles.css contains theme variables and responsive/print styles.
- script.js enhances the mobile menu and footer year.
- assets/Irfan_Soudagar_CV.pdf is an unchanged copy of the supplied three-page CV, linked for download.
- .nojekyll enables direct static serving on GitHub Pages.

## Sources

Updated from the user-supplied CV_Irfan.pdf. Publication metadata, appointment dates, education, teaching, and LinkedIn come from that source. The website email, irfans@nus.edu.sg, was provided later by the user. Publication, thesis, and paper links were extracted from the PDF's embedded links. The Centre for Maritime Studies link is its research-updates listing, not a direct paper URL.

Five publications are separated from two working/discussion papers. Under-review status is explicitly attributed to the supplied CV and has not been independently refreshed. Research descriptions summarize the CV. The current NUS department is unspecified because the CV does not identify it. The downloadable CV is unchanged and still contains the earlier email address and a phone number.

## Remaining placeholders

Add a professional photograph and verified Google Scholar, ORCID, and GitHub URLs. Replace .portrait-space with an image in assets/, with descriptive alt text and explicit dimensions. Profile placeholders are plain text, not dead links.

## GitHub Pages later

Copy this folder's contents into the chosen repository root, including assets/ and .nojekyll. Enable GitHub Pages for the intended branch and root folder. All local paths are relative, supporting both a user-site domain and a repository subpath. No repository, account, or domain is assumed. The website has not been published.

After choosing a public URL, add canonical metadata and a sitemap using that URL. Review the placeholders and downloadable CV before publishing. Replace the PDF when updating the CV, then synchronize the visible records.

## Accessibility and checks

Preserve the single h1, section headings, skip link, visible keyboard focus, and menu ARIA attributes. Native research disclosures work without JavaScript. The mobile menu supports Escape and moves keyboard focus to selected sections. Reduced motion and print styles are included. Check narrow/wide layouts and long titles after edits.

## Compact overview
The homepage leads with optimization and decision analytics across facility location, routing, logistics, manufacturing, and maritime applications. Two publications and three recent appointments are visible initially; additional publications, career history, education, teaching, and maritime projects use native expandable sections. All records remain in the HTML and the full CV remains downloadable.

## Background artwork
Generated with the built-in image-generation tool and saved as assets/research-background.png. Prompt: Refined abstract optimization landscape with delicate contour curves, connected network nodes, translucent layered surfaces, white and pale cool blue with restrained teal/navy, wide 3:1 composition, quiet left half for text, detail at the right and lower edge; no text, logos, ships, people, or UI. It is decorative, applied behind the hero with text contrast preserved. Main content uses a wider 1600px maximum with responsive side margins.

## Visual direction
The profile layout uses a blue navigation bar, a circular photograph placeholder, clear sans-serif type, white content, and restrained pale blue section shading. This was informed by the user-provided academic website reference at https://long-he.github.io/. The existing abstract optimization artwork remains a subtle background behind the profile. The user-provided reference supplies design direction only; its biographical content is not used as a source for this site.

## Background revision
The active hero asset is assets/research-background-v2.png, edited with the built-in image-generation tool from the original abstract optimization landscape. Edit prompt: preserve the wide layered contour and network composition, quiet light left side, and detailed right/lower edge; deepen the blues and increase definition without adding text or objects. The original asset remains in assets/ for easy comparison. CSS uses a lighter overlay so the stronger image is visible while the text stays readable.
