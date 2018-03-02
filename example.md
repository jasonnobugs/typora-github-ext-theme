[TOC]

# 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
```



# 强调

```markdown
*这是一段斜体文字*
_这是一段斜体文字_

**这是一段粗体文字**
__这是一段粗体文字__
```


*这是一段斜体文字*
_这是一段斜体文字_

**这是一段粗体文字**
__这是一段粗体文字__



# 列表

```markdown
* 无序列表项1
  * 无序列表项1-1
  * 无序列表项1-2
* 无序列表项2
- 无序列表项2-1
- 无序列表项2-2
  - 无序列表项2-1
  - 无序列表项2-2
```

* 无序列表项1
  * 无序列表项1-1
  * 无序列表项1-2
* 无序列表项2
- 无序列表项2-1
- 无序列表项2-2
  - 无序列表项2-1
  - 无序列表项2-2

```markdown
1. 有序列表项1
   1. 有序列表项1-1
   2. 有序列表项1-2
2. 有序列表项2
   - 无序列表项2-1
   - 无序列表项2-2
```

1. 有序列表项1
   1. 有序列表项1-1
   2. 有序列表项1-2
2. 有序列表项2
   - 无序列表项2-1
   - 无序列表项2-2



# 外链

```markdow
# 图片外链
![image](http://www.zoues.com/wp-content/uploads/2015/10/u237229786256418493fm11gp0.jpg)
```
![image](http://www.zoues.com/wp-content/uploads/2015/10/u237229786256418493fm11gp0.jpg)
```markdow
# 文字外链
[点我跳转 GitHub](https://github.com/)
```
[点我跳转 GitHub](https://github.com/)



# 引用

> ​	Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
>
> **标题:**
>
> - H1 :**# Header 1**
> - H2 :**## Header 2**
> - H3 :**### Header 3**
> - H4 :**#### Header 4**
> - H5 :**##### Header 5**
> - H6 :**###### Header 6**
>
> **文本样式:**
>
> - 链接 :[Title](URL)
> - 加粗 :***\*Bold****
> - 斜体字 :**Italics\**
> - *****删除线 :~~text~~
> - *****高亮 :==text==
> - …...



# 代码

内嵌代码:

```markdown
`alert('Hello World');
```
  `alert('Hello World');`

代码块:
```markdown
​```javascript
var str = 'hello world';
console.log(str);
```
```
​```javascript
var str = 'hello world';
console.log(str);
```



# 表格

| 项目 |   价格   | 数量 |
| :--: | :------: | :--: |
| 手机 | 8888.00  |  2   |
| 电脑 | 13999.00 |  1   |
| 平板 | 7599.00  |  3   |



# 待办事宜

```markdown
- 2017年12月21日
-[x] 早晨跑步
-[x] 中午睡觉
-[x] 晚上吃鸡

- 2017年12月22日
-[x] 早晨跑步
-[ ] 中午睡觉
-[ ] 晚上吃鸡
```

- 2017年12月21日

-[x] 早晨跑步
-[x] 中午睡觉
-[x] 晚上吃鸡

- 2017年12月22日

-[x] 早晨跑步
-[ ] 中午睡觉
-[ ] 晚上吃鸡




# 流程图

```flow
flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```

