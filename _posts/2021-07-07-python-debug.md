---
layout: post
title: 一行代码摆脱 Python Debug 烦恼
tags: [python, debug]
excerpt_separator: <!--more-->
---

```python
import pdb; pdb.set_trace()
```

另外，请大家真的不要在这样写代码了：

![vtable]({{ '/assets/img/posts/nni_bug.png' | relative_url }})

（它浪费了我整整一个晚上去 de

（如果没有上面那行代码，可能要两晚
