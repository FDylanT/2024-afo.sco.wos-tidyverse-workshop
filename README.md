# Journey into the `tidyverse`

## https://github.com/FDylanT/2024-afo.sco.wos-tidyverse-workshop

The code contained in `tidyverse-ornith.Rmd` (rendered HTML to come [here](https://fdylant.github.io/2024-afo.sco.wos-tidyverse-workshop/tidyverse.html)) provides a walkthrough of wrangling and visualising elements of a mock dataset using an assortment of functions from packages contained within the [`tidyverse`](https://www.tidyverse.org/packages/), including `dplyr`, `tidyr`, `stringr`, `readr`, and the ever-wonderful `ggplot2`, among others.

The official cheatsheets for each core `tidyverse` package and a couple of additional ones can be found at the links below:
* [Data visualization with `ggplot2`](https://rstudio.github.io/cheatsheets/data-visualization.pdf)
* [Data transformation with `dplyr`](https://rstudio.github.io/cheatsheets/data-transformation.pdf)
* [Data tidying with `tidyr`](https://rstudio.github.io/cheatsheets/tidyr.pdf) (+ a snippet dedicated to `tibble`)
* [Data import with `readr`, `readxl` & `googlesheets4`](https://rstudio.github.io/cheatsheets/data-import.pdf) -- note that `readxl` and `googlesheets4` are not "core" `tidyverse` packages and so must be individually loaded (i.e. via `library(readxl)`).
* [Applying functions with `purrr`](https://rstudio.github.io/cheatsheets/purrr.pdf)
* [String manipulation with `stringr`](https://rstudio.github.io/cheatsheets/strings.pdf)
  * CRAN guide to [regular expression syntax in R](https://cran.r-project.org/web/packages/stringr/vignettes/regular-expressions.html)
* [Handling factors with `forcats`](https://rstudio.github.io/cheatsheets/factors.pdf)

Bonus:
* [Handling dates and times with `lubridate`](https://rstudio.github.io/cheatsheets/lubridate.pdf) -- must also be individually loaded via `library(lubridate)`

For an introduction to spatial data/mapping in R using `ggplot2`/`tidyverse` syntax, [this demo](https://github.com/FDylanT/2023-wos-geospatial-workshop) walks through some methods and options.

Please feel free to reach out to me at dylan.titmuss@whoi.edu with any questions or comments!
