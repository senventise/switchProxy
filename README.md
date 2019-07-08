# switchProxy
## 灵感来源
有时候需要暂时关闭代理，但kde的代理设置藏的很深，切来切去很麻烦，就写了个小工具，可以放在pannel上，一键切换。
## 实现
感谢[为KDE桌面环境快速设置系统代理](https://whoisnian.com/2019/03/29/%E4%B8%BAKDE%E6%A1%8C%E9%9D%A2%E7%8E%AF%E5%A2%83%E5%BF%AB%E9%80%9F%E8%AE%BE%E7%BD%AE%E7%B3%BB%E7%BB%9F%E4%BB%A3%E7%90%86/)，提供了具体的解决方法，即使用`kreadconfig5`和 `kwriteconfig5`来读写配置。
~~ 其实直接写shell脚本应该更方便的。~~  
~~ 那么为什么要我用python呢？ ~~  
~~ 我 不 会 啊（心好累）  ~~
## 使用方法
```shell
$ git clone https://github.com/senventise/switchProxy.git
$ cd swithcProxy
$ sudo ./install.sh  #要往/usr/bin放东西，所以需要root
```
