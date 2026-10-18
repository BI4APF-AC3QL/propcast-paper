# PropCast release v55

This release contains the current reviewed manuscript (v55), its matching 117-page PDF, the v55 defense presentation, and the existing source-code/reproduction supplement. The manuscript structure and readability were revised for v55; no experiments or reported metrics were changed in that revision.

## Current files

- `manuscript/PropCast_Manuscript_v55.docx` — editable manuscript.
- `manuscript/PropCast_Manuscript_v55.pdf` — matching 117-page PDF rendering.
- `presentation/PropCast_Defense_v55.pptx` — 19-slide defense deck aligned to the v55 seven-chapter structure. It adds editable diagrams for the manuscript structure, data split, evaluation boundary, and continual-learning workflow.
- `software/PropCast_Reproduction_Supplement_v50.zip` — latest packaged code/reproduction snapshot currently available in this release. Its snapshot ends at 2026-09-12 08:17 UTC; it has not been rebuilt for the v55 manuscript release.
- `SHA256SUMS.txt` — SHA-256 checksums for all released files.
- `LICENSES.md` — license overview.

The repository-availability paragraph inside the manuscript records the repository state as v53 when that text was prepared. This release provides the current v55 manuscript; section 1.5 now summarizes the seven chapters in line with the document structure.

## Evidence and reproduction boundaries

The v55 manuscript reorganizes headings and makes limited readability corrections. It does not add experiments or change reported metrics. The software supplement remains the existing v50 package and has not been rebuilt from a clean, immutable source revision. Its internal manifest identifies packaged files.

The supplement excludes raw observations, personal contact logs, user identifiers, trained model binaries, row-level fold assignments, and external service credentials. Some inputs required to reproduce results are not included, so the package supports source inspection and selected recomputation workflows rather than complete row-by-row reproduction.

The retention period, deletion process, access controls, and secondary-use rules for user logs have not been established. Do not add raw user logs or personal data to this repository. Neither license grants rights to external datasets, personal data, third-party services, trademarks, or separately credited/excluded materials.

## Licenses and citation

Original manuscript text and author-created figures/tables in v55 are offered under CC BY 4.0, subject to `manuscript/LICENSE.md`. Original code in the reproduction supplement is offered under MIT; see `software/LICENSE.txt` and the license copy inside the ZIP. The defense deck is offered under CC BY 4.0 for original author-created material, subject to third-party exclusions.

Cite the author(s) and complete bibliographic information shown in the manuscript. For adaptations, identify the manuscript version, link to this repository and the applicable license, and describe changes. Do not imply author endorsement of a derivative.
