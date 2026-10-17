# PropCast release v52

This curated release contains the reviewed v52 manuscript and its rendered PDF, plus a v50 code and reproduction supplement. Licenses are scoped separately: author-owned original manuscript material is offered under CC BY 4.0; original code in the supplement is offered under the MIT License. See the notices in `manuscript/` and `software/`.

## Contents

- `manuscript/PropCast_Manuscript_v52.docx` — editable manuscript.
- `manuscript/PropCast_Manuscript_v52.pdf` — matching 116-page rendering.
- `manuscript/LICENSE.md` — manuscript license scope and attribution instructions.
- `software/PropCast_Reproduction_Supplement_v50.zip` — source and experiment materials with an internal file-level SHA-256 manifest and MIT license.
- `software/LICENSE.txt` — MIT License text for the original code in the supplement.
- `SHA256SUMS.txt` — checksums of released artifacts and license notices.

## Version and evidence boundaries

The manuscript is v52. The software supplement is the existing v50 package; it has not been rebuilt from a clean, immutable source revision. Its internal manifest identifies the packaged files. The v52 editorial changes correct cross-references; packaging did not run experiments, train models, or recompute reported metrics.

The supplement excludes raw observations, personal contact logs, user identifiers, trained model binaries, row-level fold assignments, and external service credentials. Some inputs required to reproduce results are not included, and the runtime snapshot in the supplement ends at 2026-09-12 08:17 UTC. The package supports source inspection and selected recomputation workflows; it is not complete row-by-row reproduction.

The retention period, deletion process, access controls, and secondary-use rules for user logs have not been established. Publication of code does not establish data-governance rules. Do not add raw user logs or personal data to this repository. Neither license grants rights to external datasets, personal data, third-party services, trademarks, or materials identified as excluded.

## Citation

Cite the author(s) and complete bibliographic information shown in the manuscript. For adaptations, identify version v52, link to this repository and the applicable license, and describe changes. Do not imply author endorsement of a derivative.
