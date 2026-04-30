+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
translationKey: "{{ .Name | replaceRE "\\..*$" "" }}"
+++