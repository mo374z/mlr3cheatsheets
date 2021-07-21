# mlr3cheatsheets

Cheatsheets of mlr-org packages

<!-- badges: start -->
![Render](https://github.com/mlr-org/mlr3cheatsheets/workflows/tic/badge.svg?branch=main)
<!-- badges: end -->

## Cheatsheets

- [mlr](https://cheatsheets.mlr-org.com/pdf/mlr.pdf)
- [mlr3](https://cheatsheets.mlr-org.com/pdf/mlr3.pdf)
- [mlr3pipelines](https://cheatsheets.mlr-org.com/pdf/mlr3pipelines.pdf)
- [mlr3tuning](https://cheatsheets.mlr-org.com/pdf/mlr3tuning.pdf)
- [mlr3fselect](https://cheatsheets.mlr-org.com/pdf/mlr3fselect.pdf)

## Instructions

(For internal use only)

1. Install [cheatdown](https://github.com/be-marc/cheatdown).
2. Edit R Markdown file.
  * Force section to new column with `column_breaks` in yml header.
  * Add second page with `<div class="page_break"></div>`.
  * Use `results='hide'` for executable code chunks.
3. Preview cheat sheet with `cheatdown::preview_chrome()`.
4. Check pdf version with `cheatdown::print_pdf()`.
5. Upload R Markdown and image files. Do not upload `.pdf`-versions.
6. The pdf versions are build on github actions and deployed to `gh-pages`.
