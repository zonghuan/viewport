## 视口
一个针对桌面设计的界面一般都不能很好的适用移动端，我们发现响应式设计在这个问题上可以帮我们很大的忙。下面是个典型的例子：
~~~~
<meta name="viewport" content="width=device=width,initial-scale=1">
@media screen and (max-width: 480px){
    //书写宽度不超过480px的样式
}
~~~~
假如你已经见过上面的两段代码，
