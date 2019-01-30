---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author: "Eric Patrick"
venue: "Planet Sarbez"
cost: "$"
bands: [
    ""
    ]
featured_image: ""
website: ""
---



## Related Shows

{{ range first 10 ( where .Site.RegularPages "Section" "shows" ) }}
* {{ .Title }} ({{ .Date }}) {{ end }}
