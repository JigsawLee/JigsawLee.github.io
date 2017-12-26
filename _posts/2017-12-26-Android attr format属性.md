---
layout:     default
title:      Android attr format 属性
subtitle:   Android自定义view attr的format属性
date:       2017-12-26
author:     JigsawLee
header-img: img/post-bg-ios9-web.jpg
catalog: true

---

属性名称使用小驼峰命名规则
1. reference:某一资源的id
ImageView 的src属性
2. color:色值
TextView 的textColor属性
3. boolean: 布尔值
Button 的focusable属性
4. dimension: 尺寸值
View 的layout_width
5. float:浮点值
ImageView 的 alpha属性
6. integer: 整型
TextView 的 maxLines
7. string: 字符串
TextView 的text属性
8. fraction: 百分数
rotate动画 的pivotX属性
9. enum:枚举值
LinearLayout的orientatin属性vertical/horizontal
10. flag:位或运算
activity的windowSoftInputMode属性

属性定义时可以指定多种类型值：
```
<declare-styleable name = "名称">
         <attr name = "background" format = "reference|color" />
</declare-styleable>
```

[自定义属性](http://blog.csdn.net/pgalxx/article/details/6766677)
