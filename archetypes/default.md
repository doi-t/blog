---
title: "{{ replace .Name "-" " " }}"
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02 15:04" }}
lastmod: {{ now.Format "2006-01-02 15:04" }}
draft: true
---
