# Final 193DD Project
## Final Project on Bird Abundance - Ethan, Alex, Zelda

## General Information
This repository contains data and code to explore patterns in waterbird abundance in relation to water elevation at North Campus Open Space.

To work with the code in this repository, you will need the following code chunk:

```
# general use
library(tidyverse)
library(here)
library(janitor)
library(snakecase)
library(dplyr)

#Wrap Axis Label
library(scales)

#reading .xlsx files
library(readxl)

# visualize missing data
library(naniar)

# visualizing
library(patchwork)
library(flextable)
library(ggridges)
library(NatParksPalettes)
library(paletteer)
library(ggrepel)
library(cowplot)
```
## File Structure

```
.
├── README.md
├── code                                          
│   ├── bird_abundance.pdf
│   ├── birdabundance.qmd
|   ├── citations
|       ├── LHA_B158.pdf
|       └── LHA_B158.pdf
|   ├── preliminary sketches
|       └── Elective Artwork.pdf
├── data
│   ├── birds.csv     # bird data
|   └── venoco-water.csv     # water elevation data
└── final_193DD_proj.Rproj
```
## Rendered Output
The rendered document for our final project pdf is [here](https://github.com/EthanCastelazo/final_193DD_proj/blob/9d7046b60c8d4d7f1d97c4342fcebc861694e13e/code/bird_abundance.pdf)

The rendered document for our final paper pdf is [here](https://github.com/EthanCastelazo/final_193DD_proj/blob/ca3108aa033c9539b03bfa33c128f8e8ea8e389e/final%20paper/Final_Paper.pdf)