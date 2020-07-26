---
title: Hexo icarus 主题如何加入 TIDIO及时聊天

date: '2020-07-25 00:00:01'
article:
    highlight:
        theme: atom-one-dark
---

准备工具[TIDIO](https://www.tidio.com "TIDIO"),去官网注册帐号，按提示操作

在路径themes/hexo-theme-icarus/layout/common/head.jsx 文件底部里加入      

```  themes/hexo-theme-icarus/layout/common/head.jsx
<script src="https://code.tidio.co/你的公钥" async></script>
```

公钥去DIDIO自己申请

![](https://www.tidio.com/wp-content/themes/tidio-wptheme-2.3.20/assets/logo_tidio.svg)





