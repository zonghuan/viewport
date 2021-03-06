## 视口

这里会说三个视口：[布局视口](https://github.com/zonghuan/viewport/blob/master/%E8%A7%86%E5%8F%A3/%E5%B8%83%E5%B1%80%E8%A7%86%E5%8F%A3.md)，[视觉视口](https://github.com/zonghuan/viewport/blob/master/%E8%A7%86%E5%8F%A3/%E8%A7%86%E8%A7%89%E8%A7%86%E5%8F%A3.md)，[理想视口](https://github.com/zonghuan/viewport/blob/master/%E8%A7%86%E5%8F%A3/%E7%90%86%E6%83%B3%E8%A7%86%E5%8F%A3.md)。它们有如下性质：

* 在桌面浏览器，浏览器窗口就是约束你的css布局的窗口(称为布局视口或者初始包含块)。它决定了用户可以看到什么。

* 在手机上，视口被拆分成2个：布局视口回限制你的css布局；视觉视口会决定用户能看到什么；

* 移动端浏览器还有一个理想视口，它是对于特定设备上的特点浏览器的布局视口的一个理想尺寸

* 可以把布局视口的尺寸设置为理想视口，这就是响应式设计的基础。

虽然视口的概念并不新，但将它分为三个是一件新鲜事。这就是为什么你会经常在文章或者W3C推荐标准中看到视口的字样，却没看到时哪一种。通常根据语境你就能弄清楚是在将哪个视口。 