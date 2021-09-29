---
title: "Second"
date: 2021-09-28T17:12:24-07:00
tags: ["tag2"]
menu: "pots"
draft: false
---

This part will be shown in the preview

<!--more-->

# Mathjax block
{{< mathjax/block >}}
For \(a \in A\)
\[a \ne 0\]
{{< /mathjax/block >}}

Inline shortcode {{< mathjax/inline >}}\(a \ne 0\){{< /mathjax/inline >}} with
Mathjax.{{< sidenote >}}This a sidenote example{{< /sidenote >}}

# Tikzjax block
---

{{< tikzjax >}}
\tikz \draw[thick,rounded corners=8pt]
(0,0) -- (0,2) -- (1,3.25) -- (2,2) -- (2,0) -- (0,2) -- (2,2) -- (0,0) -- (2,0);
{{< /tikzjax >}}

---
