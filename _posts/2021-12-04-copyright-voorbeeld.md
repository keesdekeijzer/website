---
layout: post
title: Copyright voorbeeld code
date: 2021-12-04
tags: copyright
description: de code die nodig is voor copyright melding
---
# Copyright code

```
<p>&copy; &lbrace;&lbrace; 'now' | date: '%Y' &rbrace;&rbrace;, &lbrace;&lbrace; shop.name | link_to: '/' &rbrace;&rbrace;</p>
<p>&lbrace;&lbrace; powered_by_link &rbrace;&rbrace;</p>
```

<p>&copy; {{ 'now' | date: '%Y' }}, {{ shop.name | link_to: '/' }}</p>
<p>{{ powered_by_link }}</p>
