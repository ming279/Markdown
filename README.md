# <center><font face="仿宋" color=red>Markdown入门</font>
</center>

### <center><font face="宋体" color=blue>wjm</center></font>

<table><tr><td bgcolor=yellow>背景色yellow</td></tr></table>  <br>
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
|first|second|third|
| :---- | :-----:|:--- |
|吃饭|睡觉|打豆豆|
## 换行
随便打一串数字<br>成功换行

*斜体*
==高亮==
**粗体**
***粗斜体***
~~删除~~
<u>下划线</u>
代码块  `<u></u>`
- 注脚
  请大家多多三连[^1]支持

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

#### 导出PDF

  [^1]:点赞，投币，收藏；
  要注明注脚是什么
  
