---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author: "{{ replace .Name "_" " " | author }}"
---

