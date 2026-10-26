# Lab 02: Data Wrangling for Dataframes

Zoey Liu, RE 519.

## Files

- `lab-02.Rmd`: lab text, code, and written responses.
- `lab-02.html`: rendered report.
- `data/kingco_homes.rds` and `data/kingco_sales.rds`: saved input datasets.
- `images/`: the original lab diagrams, extracted from its supplied HTML.
- `session-info.txt`: R and package versions used for rendering.

## Run in RStudio

Open `lab-02.Rmd` and click **Knit**. On a new installation, first run:

```r
install.packages(c("tidyverse", "rmarkdown", "cleanrmd"))
```

RStudio supplies Pandoc. Alternatively, from this folder:

```r
rmarkdown::render("lab-02.Rmd")
```

The code uses relative paths and includes its input data. No separate `kingCoData` installation is required. The instructional diagrams are included locally. MathJax is an online resource; internet access may be needed for math formatting. The missing `custom.css` reference was removed, leaving the supplied almond theme.

## Data source

Andy Krause's [kingCoData](https://github.com/andykrause/kingCoData), version 0.4.0, source commit `91f67910f0789f798cda19c76e7b493315ad7ca8`. These RDS files preserve the complete datasets from the locally installed package. The course describes these as data through December 2023.

The original lab credits Siman Ning, Feiyang Sun, Haoyu Yue, Christian Phillips, and Charles Lanfear. Original lab instructions and acknowledgements remain in the Rmd.
