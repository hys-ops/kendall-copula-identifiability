# Kendall distributions identify Archimedean copulas in every finite dimension

An anonymous manuscript dated 24 November 2026. For each fixed finite dimension d ≥ 2, equality of the population Kendall distributions implies equality of the Archimedean copulas on the entire closed unit cube. Corresponding generators differ only by a positive rescaling of their arguments.

- [Landing page](index.html)
- [Complete preprint](artifacts/kendall-identification.pdf)
- [LaTeX source, Lean sources, pinned dependencies and verification log](artifacts/kendall-source-and-lean.zip)

The Lean verification starts with the classical Williamson/radial representation as input and ends at `KendallSample.identifies`. The statistical applications in manuscript §5 are outside the formalization. The supplied verification log records compilation and kernel replay of 15 local modules and axiom audits of 13 declarations.

## GitHub Pages layout

`index.html` is self-contained except for its two relative download links. Place the contents of this directory at an intended Pages content root; retain `.nojekyll` and the relative `artifacts/` paths. No build step or externally loaded asset is needed. This bundle does not configure or deploy Pages.
