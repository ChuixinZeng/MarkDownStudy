###HBuilderDemo3

## 水平分割线

    <hr>Horizontal Rule代表水平分隔

---

    三种形式作为水平分割线使用，前面要留空行，不要写文字
    <hr>Horizontal Rule代表水平分隔

***

    <hr>Horizontal Rule代表水平分隔
    
___

    <hr>Horizontal Rule代表水平分隔

## HTML代码  

markdown没有让文字水平居中的效果，所以可以借助HTML

<p align='center'>Hello World!</p>

<!--

把注释信息放在块注释里面
注释信息是不会出现在web浏览器里面的，会被自动忽略掉
--!>

<!-- 这是HTML的行注释信息 -->

<p align='center'>
<img align='center' src='https://www.baidu.com/img/bd_logo1.png'/>
</p>


## 表格

### 标准表格（推荐）

| 这 | 是 | 表头 |
|----|:----:|----:|
| 默认是左对齐，左对齐 | cell2居中效果，居中效果| cell3右边对齐|
| **row2加粗** | row2 | ![][baidu_logo]|
|image | demo | [百度] |

### 精简表格格式（去掉左右边框线）

这 | 是 | 表头 |
----|:----:|----:
默认是左对齐，左对齐 | cell2居中效果，居中效果| cell3右边对齐
row2 | row2 | row 2

##GFM

GitHub Floored MarkDown,GFM,是GITHub具有自身特色的MarkDown工具

- 任务列表task list

- [] 项目1
- [] 项目2
- [] 项目3

- [x] 项目1
- [x] 项目2
- [x] 项目3

- emogi表情符号

:smile:


<!-- 注释信息 -->

[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[百度]: http://www.baidu.com
