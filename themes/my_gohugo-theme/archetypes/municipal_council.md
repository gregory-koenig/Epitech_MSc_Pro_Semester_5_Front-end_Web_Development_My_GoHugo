---
title: "{{ replace .Name "-" " " | title }}"
firstNames: ""
lastName: "{{ .Name | upper }}"
role: "Deputy"
photo: "images/default.jpeg"
---

