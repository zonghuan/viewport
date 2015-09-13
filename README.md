## 视口
一个针对桌面设计的界面一般都不能很好的适用移动端，我们发现响应式设计在这个问题上可以帮我们很大的忙。下面是个典型的例子：
~~~~
<meta name="viewport" content="width=device-width,initial-scale=1">
@media screen and (max-width: 480px){
    //书写宽度不超过480px的样式
}
~~~~
假设你已经见过上面的两段代码，并且对响应式设计如何工作有些了解。但你不一定知道所有复杂的细节，这就是本文讨论的内容，其中包括像素、视口、分辨率、meta视口。
