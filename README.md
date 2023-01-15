# 标题修饰符（一级标题）
## 标题修饰符（二级标题）
### 标题修饰符（三级标题）
#### 标题修饰符（四级标题）
##### 标题修饰符（五级标题）
## 正文与换行
编辑一段测试正文内容<br>
第二段测试文本，在Markdown语言中\<br\>为换行符号
## 字体修饰符
#### 字体加粗
一段测试**文本**，其中要将**文本**两字用粗体修饰，在需要修饰的正文左右两侧用\*\*包含<br>
#### 斜体
一段*测试*文本，其中*测试*两字变为斜体，在需要修饰的正文左右两侧用\*包含<br>
#### 粗斜体
一段测试文本，其中***修饰***两字变为粗斜体，在需要修饰的文本左右包含\*\*\*<br>
#### 删除线
一段测试文本，其中~~有一段机密~~的信息，机密信息加入删除线的操作，其中两侧用~~包含<br>
#### 关键字凸显
一段测试文本，`珍贵`两字变为凸显关键，需要在文本左右两侧用\`包含<br>
#### 引用
>一级引用
>>二级引用
>>>三级引用
>>>>四级引用
## 列表
####有序列表
1. 进程知识
   1. 进程间通信
      	1. 管道
	2. MMAP
	3. 消息队列
   2. 进程关系
   3. 进程安全
2. 线程知识
3. 信号知识
4. 网络知识
#### 无序列表
* 进程知识
   * 进程间通信
      	* 管道
	* MMAP
	* 消息队列
   * 进程关系
   * 进程安全
* 线程知识
* 信号知识
* 网络知识
#### 混合列表
* 热门游戏
  1. 鹅鸭杀
  2. CSGO
  3. 道德与法治5
  4. 王者荣耀
1. 获奖游戏
   * GTA
   * 老马
   * 原神
   * FIFA23
## 表格
游戏名|游戏价格|游戏评分|游戏热度|
--|:--:|:--:|--:|
GTA|299|90|75%
FIFA23|299|89|89%
原神|299|98|20%
## 代码片段
```c
#include <stdio.h>
#include <unistd.h>
#include <string.h>

int main(){
	printf("test optput...\n");
	return 0;
}
```
```bash
git add filename
git rm filename
git remote add origin SSH_address
echo "数据回显"
```
```cpp
#include <iostream>
using namespace std;
int main(){
	cout<<"hello world"<<endl;
	return 0;
}
```
```java
//java代码
```

## 插入图片和链接
[bilibili](https://www.bilibili.com "点击打开哔哩哔哩")<br>
[github](https//github.com "点击打开GitHub网站")

![壁纸截图]("https://pic.rmb.bdstatic.com/bjh/5ecc7ab7dd8624cd44731d6957c330d03752.jpeg@h_1280" "壁纸图片")
### 上传的图片地址不允许是本地图片地址，将本地图片上传到某个图片网站，生成一个图片的网络url（网络地址），用网络地址，GitHub就可以访问加载图片了
