+++
date = '2025-04-13T18:24:21+03:00'
draft = false
title = 'My Mathjax'
+++

## Will Mathjax work?

It does.

\\[ x = {-b \pm \sqrt{b^2-4ac} \over 2a} \\]

What have i done?

I added this piece of code into `public/index.html` and it suddenly works on the index (i.e. Home page). The I added the same piece of code into the `theme/ananke/layouts/default/baseof.html` and it also works on the post.

```
<script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```