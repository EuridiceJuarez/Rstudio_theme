# Rstudio_theme

Pink inspired RStudio theme.

To add these themes to your RStudio, follow the steps outlined below.

Required packages:

rstudioapi: install.packages("rstudioapi")
library(rstudioapi)

Add Eury_pink to RStudio:
Eury_pink <- "https://raw.githubusercontent.com/emhogg/barbie_r_studio_themes/main/Barbie_Light.rstheme"
rstudioapi::addTheme(Eury_pink, apply = TRUE)
