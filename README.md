# css_selector

实现一个 DOM/CSS 的选择器(如 querySelector 这种)

一般的思路是获取到顶部的元素，如 `document`，然后不断往下循环，匹配规则来获取到元素

1. 我们会先列取出所有的 CSS 的选择器的语法，如 类选择器/全体选择器/class/id/伪类选择器 这些规则

2. 然后在获取到顶部元素后，不断往下循环，然后根据当前元素是否能够匹配上我们输入的匹配规则


## 参考
1. [my-querySelector](https://github.com/Homework-of-Geekbang/my-querySelector)
2. [CSS_selector_engine](https://github.com/termi/CSS_selector_engine)
3. [CSS 选择器介绍](./参考文章/选择器-1.md)
