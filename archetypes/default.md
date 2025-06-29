---
date: "{{ .Date }}"
draft: false
title: '📃 {{ replace .File.ContentBaseName "-" " " | title }}'
cascade:
  type: docs
comments: true
---
