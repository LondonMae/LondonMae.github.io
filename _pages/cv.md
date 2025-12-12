---
# layout: cv
permalink: /cv/
title: resume
nav: true
nav_order: 5
cv_pdf: resume.pdf # you can also use external links here
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
toc:
  sidebar: left
---

<script type="text/javascript">
  window.location.href = "{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}";
</script>
<noscript>
  <a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}">Click here to view the PDF</a>
</noscript>
