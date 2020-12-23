![daniel-leone-g30P1zcOzXo-unsplash.jpg](https://i.loli.net/2020/10/15/ot8gXYVCifcs6FU.jpg)


1.git clone 去克隆一个repo速度特别慢
  - 解决方案:使用github国内镜像：github.com.cnpmjs.org；<br>附上原博客链接[git clone超级慢怎么办?](https://blog.csdn.net/lemon4869/article/details/106849352)


2.ubuntu修改hosts
```
sudo vim /etc/hosts
#在文件最后一行添加ip
sudo /etc/inti.d/networking restart
```


3.ubuntu将默认的python2切换为python3
  ![2020-10-21 21-08-32屏幕截图.png](https://i.loli.net/2020/10/21/LfIGj5oAcDkBMH8.png)
  
  
 上述方法有误，正确方法看这篇博客[Ubuntu 18.04将Python3设为默认Python版本](https://m.linuxidc.com/Linux/2019-12/161629.htm)


4.ubuntu下只下载electron ssr不能科上，还需要更改系统的网络设置：
  ![2020-12-23 16-19-54 的屏幕截图.png](https://ae02.alicdn.com/kf/U523b82fc6d544e57a69ef5fea8f53dc7J.png)
