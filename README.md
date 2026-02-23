# Spotify_popularity_research
DATS 6101 group project
---
title: "Project 1: Spotify Track Popularity and Musical Features"
author: "Basay Tayfun, Ethan Terrill, & Isaac Kim"
date: "`r Sys.Date()`"
output:
  html_document:
    code_folding: hide
    number_sections: true
    toc: yes
    toc_depth: 3
    toc_float: yes
---
```{r init, include=FALSE}
library(ezids)
```
```{r setup, include=FALSE}
knitr::opts_chunk$set(warning = FALSE, message = FALSE, fig.width = 8, fig.height = 5)
options(scientific = TRUE, digits = 3)
```
# Introduction
Our project...
**SMART Question:**
# Data loading and inspection
```{r load_data}
spotify <- read.csv("dataset.csv", header = TRUE)
str(spotify)
```
