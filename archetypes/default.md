---
title: '{{ if gt (len .File.ContentBaseName) 25 }}{{ substr .File.ContentBaseName 0 25 | title }}...{{ else }}{{ replace .File.ContentBaseName "-" " " | title }}{{ end }}'
date: '{{ .Date }}'
tags: []
author: "e90rm"
showToc: true
TocOpen: false
draft: true
description: "Desc Text."
canonicalURL: "https://e90rm.com/ADDD"
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: false
UseHugoToc: true
---
