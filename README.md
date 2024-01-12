# 一级标题
## 二级标题
### 三级标题
#### 四级标题
\# 为标题修饰符
## 正文内容
直接编辑正文内容即可，但是如果需要换行，使用\<br\>,为换行符<br><br>
第一行数据
第二行数据<br>
第三行数据
## 字体修饰符

**粗体** 两对\*包含为粗体

*样式* 一对\*包含为斜体

***粗斜体*** 三对\*包含为粗斜体

这是一段描述信息，但是`关键字`被凸显

~删除线效果~ 一对\~包含

## 引用

需要引用可以使用\> ,多级引用可以相互包含

> 一级引用
>> 二级引用
>>> 三级引用

### 分割线

使用五个\*即可实现分割线特效

第一段数据

*****

第二段数据

##列表

如果使用\*表示无序列表 如果使用1.2.3.4.均为有序列表

* 物理学
  * 粒子物理
  * 原子核物理
  * 凝聚态物理
* 计算机科学
  * 网络通信
    * 套接字
    * DNS域名解析器
    * 内网搭建，链路层串联

1. 物理学
   1. 粒子物理
   2. 原子核物理
   3. 凝聚态物理
2. 计算机科学
   * 套接字
   * DNS域名解析器
   * 内网搭建，链路层串联

## 代码插入 

插入不同的代码，要声明代码块

```c
   #include<stdio.h>
   int main(){
	printf("hahah");
	return 0;
   }
```

c cpp java bash(终端命令) python/py

## 超链接

[bilibili](https://www.bilibili.com "点击进入B站")
  连接标题      链接地址              悬停标题

## 插入图片
![图片](https://p0.ssl.qhimgs1.com/sdr/400__/t01251cf123abdc1124.p "开心图片") 
 如果需要在github中显示图片数据，需要网络图片地址，将图片上传到某个网络生成图片的url，而后github才可以访问加载这张图片

## 表格

姓名|技能|伤害
--|:--:|--
刘备|腿长|20
关羽|胡子长|80
张飞|彪悍|70
