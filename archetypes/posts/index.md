---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
images:
  - 
tags:
  - 
url: /{{ partial "slugify.html" .Name }}

---
