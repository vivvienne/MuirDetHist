---
layout: page
title: test page
permalink: /test_page
---

inline 2 dollars: $$x^2+y^2=z^2$$

display:

$$x^2+y^2=z^2$$

$$
\begin{CD}
A @<<< B @>>> C\\
@. @| @AAA\\
@. D @= E
\end{CD}
$$

```yaml
markdown:            kramdown
highlighter:         rouge
permalink:           /:title
plugins:             [jekyll-paginate, jekyll-sitemap, jekyll-feed, jekyll-seo-tag]
```