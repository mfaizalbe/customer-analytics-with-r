# Customer Analytics with R

## 📌 Overview

This repository contains my assignments for the **Customer Analytics with R** course.
Each assignment lives in its own folder under `assignments/`, together with the dataset it uses.

## 🎯 Objectives

* Analyse customer data to find patterns and trends.
* Segment customers based on behaviour and demographics.
* Visualise key insights using R packages like ggplot2 and dplyr.
* Apply basic predictive analytics to understand customer lifetime value or churn.

## 🗂️ File Structure

```
assignments/
├── tha1/                       # Take-Home Assignment 1
│   ├── 2DTHA1_Faizal.Rmd
│   ├── 2DTHA1_Faizal.html
│   └── data/restaurant.xlsx
├── tha2/                       # Take-Home Assignment 2
│   ├── 2DTHA2_Faizal.Rmd
│   ├── 2DTHA2_Faizal.html
│   └── data/library_visits_THA2.xlsx
├── tha3/                       # Take-Home Assignment 3
│   ├── 2DTHA3_Faizal.Rmd
│   ├── 2DTHA3_Faizal.html
│   └── data/spotify_songs.csv
├── tha4/                       # Take-Home Assignment 4
│   ├── 2DTHA4_Faizal.Rmd
│   ├── 2DTHA4_Faizal.html
│   └── data/
│       ├── dlpi2d-batch9-tha4-data1.csv
│       └── dlpi2d-batch9-tha4-data2.xlsx
└── group-project/              # Group 8 project (Pioneer House residential life survey)
    ├── group_8_project.Rmd
    ├── group_8_project.html
    └── data/                   # phrl_survey.xlsx not included (survey privacy)
```

Each assignment folder is self-contained: the `.Rmd` reads its data from the local `data/` subfolder, and the `.html` is the pre-rendered output.

> **Note:** `assignments/group-project/data/` does not include `phrl_survey.xlsx` — the underlying survey data isn't shared publicly. The `.Rmd`/`.html` are kept for reference, but the script won't run standalone without that file.

## ⚙️ How to Use

1. Make sure R is installed: [CRAN](https://cran.r-project.org/)
2. Install required packages (if needed):

```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "readxl"))
```

3. Open the `.Rmd` file for the assignment you want inside `assignments/<name>/` and knit it — each one is independent, so there's no required order. Paths are relative to the assignment's own folder (e.g. `data/restaurant.xlsx`), so open the project from the repo root or set your working directory to the assignment folder before running chunks interactively.

## 📚 Notes

* Each assignment corresponds to a specific take-home assignment (THA) or the batch 9 group project.
* Visualizations and outputs are generated when running the scripts; pre-rendered `.html` versions are included for quick viewing without running R.
