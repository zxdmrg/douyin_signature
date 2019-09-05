  
  获取抖音数据一定要会计算_signature的值.网上的教程一大堆.我看了很多,也试着运行了.发现基本上都是不能用的,或者作者写的非常不清楚.自己研究了半天.写一个可以直接运行的供大家参考

### 准备工作
* 找一个分享链接 在抖音，记录美好生活！ http://v.douyin.com/5jDQWr/
* 找到页面上的tac.下面有图示
* 修改douyin.js 里面我有写注释的地方.替换为刚才找到的tac.
* 运行代码,得到跟页面上显示的同一个_signature值
* 异常错误忽略,不影响


### run
``` 
# 需要安装jsdom   npm i jsdom
#node douyin.js uid
node douyin.js 1604937842691048
```

### tac在哪里
![image](https://raw.githubusercontent.com/zxdmrg/douyin_signature/master/img/request.png)
![image](https://raw.githubusercontent.com/zxdmrg/douyin_signature/master/img/tac.png)


### 运行结果
![image](https://raw.githubusercontent.com/zxdmrg/douyin_signature/master/img/run.png)


### 补充说明
现在还有一个获取tac的动作,需要各位自己用后端获取后传过来执行.自己实现,这边就不写了

### 有问题也可以到我网站留言
www.zxdmrg.com
