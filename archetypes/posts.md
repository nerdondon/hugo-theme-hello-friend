---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: ""
draft: true
comments: false
images:
logoText: 'cat {{ .File.LogicalName }}'
tags: []
---