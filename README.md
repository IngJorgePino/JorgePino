---
# Analisis de datos exploratorios
# Titulo
Biometría de peces
# Autor
Jorge Pino
# email
jorgepinochoqueapaza@gmail.com
output: pdf_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(stats)
library(graphics)
library(readxl)
library(psych)
library(ggplot2)
```
```{r}
datos <- read_excel("lenguado.xlsx")
summary(datos)
str(datos)


