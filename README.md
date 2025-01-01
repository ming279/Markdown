# <center><font face="仿宋" color=red>Markdown入门</font>
</center>

### <center><font face="宋体" color=blue>wjm</center></font>
<span style="color: red;">这是一段红色文字</span>   
<span style="background-color: yellow;">背景色yellow</span>   
<span style="background-color: yellow;">高亮文本</span>   
每个#之后要空一格
>引用
>>二级引用

1. 标题
   - name
   - class
   - eat
2. 1. 不定标题
   2.
   3.
3. todot list
  - [x] 吃饭
  - [x] 睡觉
4. 输出
   h~2~o
## 表格
|first word|second word|third word|
| :---- | :-----:|---: |
|吃饭|睡觉|打豆豆|
## 换行
随便打一串数字<br>成功换行

*斜体*   
<mark>高亮</mark>   
```diff
+ 高亮
```
**粗体**   
***粗斜体***   
~~删除~~   
   
或<ins>下划线</ins>
代码块  `<u></u>`   
- 注脚   
  请大家多多三连[^1]支持   
下标用`<sub></sub>`   
这是一个<sub>下标</sub>格式   
代码
```<table><tr><td bgcolor=yellow>  
#include<iostream>
using namespace std;
int main()
{
     cout<<"hellow word!";
     return 0;
}

```
代码高亮：
```C++
#include<iostream>
using namespace std;
int mian()
```
## diff语法   
```diff
+ 人闲桂花落，
- 夜静春山空。
! 月出惊山鸟，
# 时鸣春涧中。
```
**超链接**
  ming279的库：https://github.com/ming279/Markdown/edit/main/README.md   
  <https://github.com/ming279/Markdown/edit/main/README.md>   
  [ming279的库](https://github.com/ming279/Markdown/edit/main/README.md)   
      更加详细的链接请[点击](https://markdown.com.cn/basic-syntax/links.html)   
**图片**   
   [通过图床]: https://imgse.com/   
**其他操作**
- 插入latex公式
   - 行内显示公式：$f(x)=a(x)+b$
   - 块内显示数学公式：$$ $$

 **html/css语法**   
 ### 流程图   
>横向结构   
 ```mermaid
 graph LR
 A[方形] -->B(圆形)
 B-->C{条件a}
 C-->|a=1| D[结果1]
C-->|a=2| E[结果2]

 ```
 >纵向结构   
 ```mermaid
 graph TD
 a[方形]-->b(圆形)
 -->c{条件a}
 c-->|a=1| d[结果1]
 c-->|a=2| e(结果2)
 ```
## 警报
> [!NOTE]
> 注意！！！

> [!TIP]
> 注意！！！

> [!IMPORTANT]
> 注意！！！

> [!WARNING]
> 注意！！！

> [!CAUTION]
> 注意！！！
#### 导出PDF

  [^1]:点赞，投币，收藏；
  要注明注脚是什么
  
