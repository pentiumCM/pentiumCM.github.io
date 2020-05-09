---
layout:     post
title:      "「Help documentation for the website」"
subtitle:   "How to use this site"
date:       2020-05-09
author:     "pentiumCM"
header-style: text
hidden:     true
tags:
    - 示例文章
---

> 我最害怕听到的一句话是
> 你已经尽力了


## 1. How to create a post
There are two styles of blog, text type and background image type.

### 1.1 text type
```
---
layout:     post
title:      "「Help documentation for the website」"
subtitle:   "How to use this site"
date:       2020-05-09
author:     "pentiumCM"
header-style: text
hidden:     true
tags:
    - 示例文章
---
```

### 1.2 background image type
```
---
layout:     post
title:      "你好"
subtitle:   "我叫陈敏, @pentiumCM"
date:       2020-05-09
author:     "pentiumCM"
header-img: "img/post-bg-miui6.jpg"
hidden:     false
tags:
    - 示例文章
---
```

When the number of post tags is greater than the set value, the tags of this article will be displayed in the FEATURED TAGS. (The set value is in the file _config.yml : featured-condition-size)