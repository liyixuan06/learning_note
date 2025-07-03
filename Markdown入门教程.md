# <center><font face="仿宋" font color=orange>Markdown入门教程</font>

## <center><font face="楷体" size=5>毛怪</font></center>

# <center>**一 准备工作**
1. **安装vscode**
2. **下载必要的插件**


# 二 基本语法
1. **标题** 
    1. # 一级标题
    2. ##  二级标题
    3. ### 三级标题

2. **引用**
   > 编辑这类文档很好用！
   >> hello,world!

3. **todolist**
   - [ ] a
  
4. **表格**

| 姓名   | 年龄 | 职业       |
|--------|:----:|-----------:|
| 张三   | 28   | 工程师     |
| 李四   | 24   | 设计师     |

| 姓名 | 年龄 | 职业 |
| ---- |:--- | ----:| 

5. **段落**
   
   - 换行？——两个以上空格然后回车
   - 分割线 
   ***
   - 字体
   
   | 字体 | 代码 |
   | :-----: | :-----: |
   | *斜体* | *   * |
   | **粗体** | **   ** |
   | ***斜粗体*** | ***   *** |
   | ~~删除~~ | ~~ ~~ |
   | ==高亮== | == == |
   | <u>下划线</u> | ' <u> </u> ' |

   - 脚注 
     请大家多多三连 [^1] 支持。


5. **代码**
    `print("Hello World")` 


    ```
    #include<iostream>
    using namespace std;
    ------
    
    ```

6. **超链接**
   - 四川大学：[https://jwc.scu.edu.cn/]
  
   - 学习资源请参考[官方文档][doc]  


7. **图片**
   - 使用图床保存图片并插入
   - [路过图床] :https://imgse.com/
   - 直接使用markdown语法插入
   - [![pVplLp4.png](https://s21.ax1x.com/2025/05/28/pVplLp4.png)](https://imgse.com/i/pVplLp4)
   - 使用html语言实现调整图片大小和位置的操作
8. **插入latex公式**
    - 行内显示公式 : $f(x)=ax+b$
    - 块内显示数学表达式
    $$
    \begin{Bmatrix}
    a & b \\
    c & d 
    \end{Bmatrix}
    $$
   


[^1]: 点赞，投币，收藏。

[四川大学] : https://jwc.scu.edu.cn/
[doc]: https://markdown.com.cn "Markdown标准指南"