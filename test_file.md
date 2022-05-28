---
title: "test_project"
output: output=github_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
library(readr)
data <- read_csv("~/Desktop/data.csv")
colnames(data)
```

```{r}
plot(1:10, type="l")
```
