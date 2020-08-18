# Elaine Kearney's Curriculum Vitae

Academic CV built using R.

- Repo forked and adapted from [seabbs/cv](https://github.com/seabbs/cv). 
- See [here](https://www.elaine-kearney.com/files/cv.pdf) for the full rendered CV.

## Structure

- `cv/cv.Rmd`: CV structure implemented as an [`{rmarkdown}`](https://rmarkdown.rstudio.com) document.
- `data/*.csv`: Data on each CV subcategory.
- `scripts/install.R`: Installs/loads all `R` dependencies using the [`{pacman}`](https://github.com/trinker/pacman) :package:.

## Tools

- The [`{vitae}`](https://docs.ropensci.org/vitae/) :package: is used to provide a CV template.
- [`{tidyverse}`](https://www.tidyverse.org) :tool: are used for data read in and manipulation.
- [`{here}`](https://here.r-lib.org) :package: for path management.
- [`{tinytex}`](https://github.com/yihui/tinytex) :package: to manage LaTex installation and additional packages.
