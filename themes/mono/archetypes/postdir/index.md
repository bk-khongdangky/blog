---
# general info
title: {{ replace .Name "-" " " | title }}
date: {{ .Date }}
slug: {{ .Name }}
summary: "summary"
# remove or change to true if you want this post to be index in sitemap.xml
index: false
# category and tags
categories:
- category
tags:
- tag
---