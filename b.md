---
title: "Title"
author: "Myself"
date: "`r format(Sys.Date(), '%d.%m.%Y')`"
output:
  xaringan::moon_reader:
    css: ["default"]
    nature:
      highlightStyle: dracula
      highlightLines: true
      countIncrementalSlides: false
---

```{r setup, include=FALSE}
options(htmltools.dir.version = FALSE)
```

.left-column[
  ## Left column title
]
.right-column[
 A whole sentence

+ one `Markdown` bullet point
{{content}}

]

--

+ a second bullet point
{{content}}

--
