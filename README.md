# Instructions

```bash
pacman -S r pandoc
```

```R
install.packages("tufte")
install.packages(c("ggplot2", "dplyr", "tidyr"))
rmarkdown::draft("tufte.Rmd", "tufte_html", "tufte")
rmarkdown::render("tufte.Rmd")
```
