---
title: "{{ replace .Name "-" " " }}"
date: "{{ .Date | time.Format ":date_medium" }}"
---