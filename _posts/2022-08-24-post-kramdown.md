---
title: "post: kramdown test"
date: 2022-08-24T13:51
categories:
  - blog
tags:
  - Jekyll
  - update
---

#         一级
##        二级
###       三级
####      四级
#####     五级
######    六级

+ down
    1. test
    2  test
- now

1. kram
    1. test
        1. test
        2. test
    2. test
    3. test
2. down
3. now

> 如果HTML标记具有属性markdown="0"，则标记将被解析为原始HTML块。  
> 如果HTML标记具有属性markdown="1"，则使用此标记中用于解析语法的默认机制。  
> 如果HTML标记具有属性markdown="block"，则标记的内容将被解析为块级元素。  
> 如果HTML标记具有属性markdown="span"，则标记的内容将被解析为span级别元素

~~~ html
script style math option textarea pre code kbd samp var
~~~

> 解析为原始 HTML

~~~ html
applet button blockquote body colgroup dd div dl fieldset form iframe li
map noscript object ol table tbody thead tfoot tr td ul
~~~

> 解析为块级元素

~~~ html
a abbr acronym address b bdo big cite caption code del dfn dt em
h1 h2 h3 h4 h5 h6 i ins kbd label legend optgroup p pre q rb rbc
rp rt rtc ruby samp select small span strong sub sup th tt var
~~~

> 解析为 span 级元素

~~~ html
<div markdown="1">This is the first part of a para,
which is continued here.
</div>
~~~