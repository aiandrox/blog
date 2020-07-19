---
title: "Chart support"
date: 2018-11-18T12:00:06+09:00
description: グラフ
draft: false
enableToc: false
enableTocContent: false
tags:
-
series:
-
libraries:
- chart
image: images/feature1/graph.png
series:
- Themes Guide
---

```chart
{
    "type": "bar",
    "data":
       {
        "labels": ["One", "Two", "Three", "Four", "Five", "Six"],
        "datasets": [{
            "label": "# of Votes",
            "data": [12, 19, 3, 5, 3, 8]
        }]
    }
}
```

```chart
    {
    "type": "line",
        "data": {
            "labels": ["One", "Two", "Three", "Four", "Five", "Six"],
            "datasets": [
            {
                "label": "# of Votes",
                "data": [12, 19, 3, 5, 2, 3],
                "backgroundColor":"transparent",
                "borderColor":"orange"
            },
            {
                "label": "Some other set",
                "data": [15, 8, 13, 5, 5, 9],
                "backgroundColor":"transparent",
                "borderColor":"#44ccff"
            }
            ]
        }
    }
```
