+++
title = "Math"
description = "Render math equations in your content"
+++

The math shortcode uses [MathJax](https://www.mathjax.org) to render math equations as SVG elements. To add an equation to a page, write the equation using TeX and surround it with `{{</* math */>}}...{{</* /math */>}}` tags.

## Example 1

```text
{{</* math */>}}
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
{{</* /math */>}}
```

{{< math >}}
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
{{< /math >}}

## Example 2

```text
{{</* math */>}}
\left( \sum_{k=1}^n a_k b_k \right)^2 
\leq 
\left( \sum_{k=1}^n a_k^2 \right) 
\left( \sum_{k=1}^n b_k^2 \right)
{{</* /math */>}}
```

{{< math >}}
\left( \sum_{k=1}^n a_k b_k \right)^2 
\leq 
\left( \sum_{k=1}^n a_k^2 \right) 
\left( \sum_{k=1}^n b_k^2 \right)
{{< /math >}}
