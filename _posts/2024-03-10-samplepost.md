---
layout: post
title:  "Template Post"
date:   2024-01-01
caption: Caption HERE
permalink: /mypost
project: true
tags: [mytag ]
thumbnail: assets/images/thumbnails/thumb1.png
categories: design
---
## self generating Gallery
{% include image-gallery.html folder="/assets/images/test" %}
## Code block

{% include codeHeader.html %}
 ```
import code  

def myfunction(
    this fucntion is cool!
)
```