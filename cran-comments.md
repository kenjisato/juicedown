## R CMD check results

0 errors | 0 warnings | 0 notes

## Resubmission

This submission addresses CRAN's NOTE about Rd cross-references requiring package anchors.

- Updated links to use anchors (e.g., `\link[knitr:knitr-package]{knitr}`, `\link[knitr:knit]{knitr::knit}`).
- Replaced accidental use of base pipe `|>` with `%>%` to keep `Depends: R (>= 3.6.0)` unchanged.

## Downstream dependencies

None known.
