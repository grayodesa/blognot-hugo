---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
images:
  - images/feature.jpg
tags:
  - 
slug: {{ partial "slugify.html" .Name }}

---
