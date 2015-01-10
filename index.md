---
title       : Slidify Test
subtitle    : nothing to see here
author      : H. Hanson
job         : 000
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete
slide 1

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!


--- .class #id 

## Slide 2
slide 2

---

slide 3

```r
fit <- lm(y ~ x1 + x2 + x3)
```

```
## Error in eval(expr, envir, enclos): object 'y' not found
```

```r
summary(fit)
```

```
## Error in summary(fit): object 'fit' not found
```

