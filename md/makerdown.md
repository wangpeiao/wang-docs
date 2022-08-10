# MakerDown 的使用

> MakerDown 的官方教程 [点我跳转](https://markdown.com.cn/)



## 1.Markdown 标题语法

**要创建标题，请在单词或短语前面添加井号 `(#) `。# 的数量代表了标题的级别**

| Markdown 语法       | HTML                    | 效果                  |
| ------------------- | ----------------------- | --------------------- |
| # 胸怀千秋伟业      | `<h1>胸怀千秋伟业</h1>` | <h1>胸怀千秋伟业</h1> |
| ## 胸怀千秋伟业     | `<h2>胸怀千秋伟业</h2>` | <h2>胸怀千秋伟业</h2> |
| ### 胸怀千秋伟业    | `<h3>胸怀千秋伟业</h3>` | <h3>胸怀千秋伟业</h3> |
| #### 胸怀千秋伟业   | `<h4>胸怀千秋伟业</h4>` | <h4>胸怀千秋伟业</h4> |
| ##### 胸怀千秋伟业  | `<h5>胸怀千秋伟业</h5>` | <h5>胸怀千秋伟业</h5> |
| ###### 胸怀千秋伟业 | `<h6>胸怀千秋伟业</h6>` | <h6>胸怀千秋伟业</h6> |



## 2.Markdown 段落

**要创建段落，就用空白行将一行或多行文本进行分隔**



## 3.Markdown 换行

**在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行(`<br>`)**

| Markdown 语法 | HTML | 效果 |
| ------------- | ---- | ---- |
|I really like`<br>` using Markdown. | `<p>I really like <br>  using Markdown.</p>` |<p>I really like <br> using Markdown.</p>|



## 4.Markdown 粗体和斜体

**要加粗文本，请在单词或短语的前后各添加两个星号（asterisks）或下划线（underscores）。如需加粗一个单词或短语的中间部分用以表示强调的话，请在要加粗部分的两侧各添加两个星号（asterisks）**

| Markdown 语法 | HTML | 效果 |
| ------------- | ---- | ---- |
| `**我是粗体**` | `<strong>我是粗体</strong>` | <strong>我是粗体</strong> |
| `__我是粗体__` | `<strong>我是粗体</strong>` | <strong>我是粗体</strong> |
| `***我是斜体***` | `<em>我是斜体</em>` | <em>我是斜体</em> |
| `___我是斜体___` | `<em>我是斜体</em>` | <em>我是斜体</em> |



## 5.Markdown 引用语法

**要创建块引用，请在段落前添加一个 > 符号。**

Markdown 语法: `> 胸怀千秋伟业，恰是百年风华` 效果如下
> 胸怀千秋伟业，恰是百年风华

> 胸怀千秋伟业，恰是百年风华
> > 胸怀千秋伟业，恰是百年风华



## 6.Markdown 列表语法

**可以将多个条目组织成有序或无序列表。**

### 无序列表

**要创建无序列表，请在每个列表项前面添加破折号 `(-)`、星号 `(*)` 或加号 `(+)` 。缩进一个或多个列表项可创建嵌套列表。**

- First item
- Second item
- Third item
- Fourth item

### 有序列表

**要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。**

1. First item
2. Second item
3. Third item
4. Fourth item



## 7.Markdown 代码语法

**要将单词或短语表示为代码，请将其包裹在反引号 (`)  中。**

| Markdown 语法 | HTML | 效果 |
| ------------- | ---- | ---- |
| ``apple  `apple` `` | `apple <code>apple</code> `| apple <code>apple</code>  |

**如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(``)中。**

**要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。**



## 8.Markdown 分隔线语法

**要创建分隔线，请在单独一行上使用三个或多个星号 `(***)`、破折号` (---)` 或下划线 `(___)` ，并且不能包含其他内容。**



## 9.Markdown 链接语法

**链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。**

**超链接Markdown语法代码：`[超链接显示名](超链接地址 "超链接title")`**

**对应的HTML代码：`<a href="超链接地址" title="超链接title">超链接显示名</a>`**

**效果如下：[跳转到百度](https://www.baidu.com "超链接title")**

### 给链接增加 Title

**链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。**

**效果如下：这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。**

### 网址和Email地址

**使用尖括号可以很方便地把URL或者email地址变成可点击的链接。**

`<https://markdown.com.cn> <fake@example.com>`

效果如下:

<https://markdown.com.cn>

<fake@example.com>

### 带格式化的链接 

`I love supporting the **[EFF](https://eff.org)**.`

效果如下：

I love supporting the **[EFF](https://eff.org)**.



## 10.Markdown 图片语法

**要添加图像，请使用感叹号 `(!)`, 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。**

**插入图片Markdown语法代码：`![图片alt](图片链接 "图片title")。`**

**对应的HTML代码：`<img src="图片链接" alt="图片alt" title="图片title">`**

**效果如下：**

![图片alt](./../images/README/1.png "图片title")



## 11.Markdown 转义字符语法

**要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符` \ `。**

`\* Without the backslash, this would be a bullet in an unordered list.`

**效果如下：**

\* Without the backslash, this would be a bullet in an unordered list.



## 12.Markdown 内嵌 HTML 标签

**对于 Markdown 涵盖范围之外的标签，都可以直接在文件里面用 HTML 本身。如需使用 HTML，不需要额外标注这是 HTML 或是 Markdown，只需 HTML 标签添加到 Markdown 文本中即可。**

### 行级內联标签

`This **word** is bold. This <em>word</em> is italic.`

This **word** is bold. This <em>word</em> is italic.

### 区块标签

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.


## 13.Markdown 表格

**要添加表格，请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道。**

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

```

效果如下：

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

**您可以通过在标题行中的连字符的左侧，右侧或两侧添加冒号`（:）`，将列中的文本对齐到左侧，右侧或中心。**


## 14. Markdown 围栏代码块

**Markdown基本语法允许您通过将行缩进四个空格或一个制表符来创建代码块。如果发现不方便，请尝试使用受保护的代码块。根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用三个反引号（```）或三个波浪号（~~~）。**

``` json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```



## 15.Markdown 脚注

**要创建脚注参考，请在方括号`（[^1]）`内添加插入符号和标识符。标识符可以是数字或单词，但不能包含空格或制表符。标识符仅将脚注参考与脚注本身相关联-在输出中，脚注按顺序编号。**

**在括号内使用另一个插入符号和数字添加脚注，并用冒号和文本`（[^1]: My footnote.）`。您不必在文档末尾添加脚注。您可以将它们放在除列表，块引号和表之类的其他元素之外的任何位置。**

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

效果如下：

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


## 16.Markdown 标题编号

**许多Markdown处理器支持标题的自定义ID - 一些Markdown处理器会自动添加它们。添加自定义ID允许您直接链接到标题并使用CSS对其进行修改。要添加自定义标题ID，请在与标题相同的行上用大括号括起该自定义ID。**

`### My Great Heading {#custom-id}`

相当于

```
<h3 id="custom-id">My Great Heading</h3>
```

效果如下：

### My Great Heading {#custom-id}


## 17.Markdown 定义列表

**一些Markdown处理器允许您创建术语及其对应定义的定义列表。要创建定义列表，请在第一行上键入术语。在下一行，键入一个冒号，后跟一个空格和定义。**

```
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

对应的HTML代码:

```
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

效果如下：

First Term

: This is the definition of the first term.

Second Term

: This is one definition of the second term.

: This is another definition of the second term.


## 18.markdown 删除线

**您可以通过在单词中心放置一条水平线来删除单词。结果看起来像这样。此功能使您可以指示某些单词是一个错误，要从文档中删除。若要删除单词，请在单词前后使用两个波浪号`~~`。**

`~~世界是平坦的。~~ 我们现在知道世界是圆的。`

效果如下：

~~世界是平坦的。~~ 我们现在知道世界是圆的。



## 19.Markdown 任务列表语法

**任务列表使您可以创建带有复选框的项目列表。在支持任务列表的Markdown应用程序中，复选框将显示在内容旁边。要创建任务列表，请在任务列表项之前添加破折号-和方括号[ ]，并在[ ]前面加上空格。要选择一个复选框，请在方括号[x]之间添加 x 。**

```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media



## 20.Markdown 使用 Emoji 表情

**有两种方法可以将表情符号添加到Markdown文件中：将表情符号复制并粘贴到Markdown格式的文本中，或者键入emoji shortcodes。**

### 复制和粘贴表情符号

**在大多数情况下，您可以简单地从Emojipedia 等来源复制表情符号并将其粘贴到文档中。许多Markdown应用程序会自动以Markdown格式的文本显示表情符号。从Markdown应用程序导出的HTML和PDF文件应显示表情符号。**

**Tip: 如果您使用的是静态网站生成器，请确保将HTML页面编码为UTF-8。**

### 使用表情符号简码

**一些Markdown应用程序允许您通过键入表情符号短代码来插入表情符号。这些以冒号开头和结尾，并包含表情符号的名称。**

```
去露营了！ :tent: 很快回来。

真好笑！ :joy:
```
效果如下：

去露营了！ :tent: 很快回来。

真好笑！ :joy: