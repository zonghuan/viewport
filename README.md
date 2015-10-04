## 简介
一个针对桌面设计的界面一般都不能很好的适用移动端，我们发现响应式设计在这个问题上可以帮我们很大的忙。下面是个典型的例子：
~~~~
<meta name="viewport" content="width=device-width,initial-scale=1">
@media screen and (max-width: 480px){
    //书写宽度不超过480px的样式
}
~~~~
假设你已经见过上面的两段代码，并且对响应式设计如何工作有些了解。但你不一定知道所有复杂的细节，这就是本文讨论的内容，其中包括[像素](https://github.com/zonghuan/viewport/blob/master/%E5%83%8F%E7%B4%A0.md)、[视口](https://github.com/zonghuan/viewport/tree/master/%E8%A7%86%E5%8F%A3)、[物理分辨率](https://github.com/zonghuan/viewport/blob/master/%E5%88%86%E8%BE%A8%E7%8E%87/%E7%89%A9%E7%90%86%E5%88%86%E8%BE%A8%E7%8E%87.md)、[设备像素比](https://github.com/zonghuan/viewport/blob/master/%E5%88%86%E8%BE%A8%E7%8E%87/%E8%AE%BE%E5%A4%87%E5%83%8F%E7%B4%A0%E6%AF%94.md)。
