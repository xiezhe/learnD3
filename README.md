# 第一天

> 获取元素

和DOM3 querySelector/querySelectorAll差不多拥有

- select() 匹配选择器的第一个元素

- selectAll() 匹配选择器的所有元素

同时也可以用DOM

    var oDiv = document.getElementById("div1");
    d3.select(oDiv);

| one              | more                   |
|:----------------:|:----------------------:|
| getElementById() | getElementsByTagName() |
| select           | selectAll              |

> 看状态

- empty()返回一个布尔值是不是空，是空则返回true
- node()返回第一非空的元素，如果是空返回null
- size()所选元素的个数