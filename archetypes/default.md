---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "Me"
author: ["<author1>", "<author2>"]
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "<description text>"
canonicalURL: "{{ .Name }}"
disableHLJS: true
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>"
    alt: "<alt text>"
    caption: "<text>"
    relative: false
    hidden: true
editPost:
    URL: "https://github.com/masterofbusinessadministration/blog/content"
    Text: "Suggest Changes"
    appendFilePath: true
---