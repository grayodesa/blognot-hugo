---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
images:
  - images/feature.jpg
tags:
  - 
url: /{{ partial "slugify.html" .Name }}

---
