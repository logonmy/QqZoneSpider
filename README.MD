1、次爬虫对爬取的QQ用户数量通过com.qq.qzone.user.QzoneSpider的maxQQCount控制，使用时可以设置次数量，比如需要</br>
10000个QQ用户的资料，那么maxQQCount=10000。</br>
2、qqlist.txt文件存放当前QQ的所属的所有QQ列表，注意初始化时最后一行必须换行，即敲一下“enter”键。</br>
3、初始化当前QQ空间主页地址：com.qq.qzone.user.QzoneSpider的login的方法第一行设置当前QQ的主页。</br>
4、本爬虫只在Windows下测试，需要电脑登录qq，然后在运行爬虫</br>
5、默认开发使用的是chrome浏览器。</br>
6、使用本爬虫如若造成经济或者商业纠纷与作者无关。</br>
7、此项目为大数据处理的前期数据挖掘，后期计划如图：
 ![image](https://github.com/1156721874/CrazyCode/blob/master/QqZone/src/QqZoneSpider.png)