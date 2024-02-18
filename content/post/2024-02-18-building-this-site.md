---
categories:
- Example
date: "2024-02-18"
tags:
- blogdown
title: Building this blog
---

First, I built this blog using the [**blogdown**](https://github.com/rstudio/blogdown) R package and it is deployed via Netlify. The template is **hugo-xmin**. 

I followed this amazing [R Blogdown Tutorial](https://www.youtube.com/watch?v=x-Ch0-w1UhY&list=PLpZT7JPM8_GbPiX4ibrP7ogl7GyEofZMj&index=5). You can also read this [post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/).

In R-Studio (Step 3 in this this [post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/)), use the following blogdown function to create a website with the Hugo theme “Xmin”: 

```yaml
install.packages('blogdown')
blogdown::new_site(theme = 'yihui/hugo-xmin')
```

