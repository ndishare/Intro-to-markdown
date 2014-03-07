[TOC]
# Intro to markdown
##  块级元素
### `<p>` 和 `<br />`
#### `<p>`

这是一个段落

#### `<br />`

文字中间 html <br /> 换行

### 标题
1. 1 - 6 个 #
***

> `This is an H1`
> `=============`
> `This is an H2`
> `-------------`

***
### 无序列表
*   sass
*   stylus
-   less
+   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        > 1986\. What a great season.
*   Bird

*   Magic

### 有序列表
1.   sass
2.   stylus
3.   less

### Blockquotes
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> >Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

### Code block

代码块

    <script>
        function code(){
            console.log(2)
        }
    </script>
    
```javascript
// Foo
var bar = 0;
```
    
### 分割线
---
分割
****
分割
- - -
> 分割

--------------
### table
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |

## 行内元素
### 链接
* [Github](https://www.github.com "Github")
* [Google][1]
* [Twitter][2]
[Google]: https://www.google.com (google)

### 强调
*single asterisks*

_single underscores_ \*this text is surrounded by literal asterisks\*

**double asterisks**

__double underscores__

### 代码
+ Use the `printf()` function.
+ ``There is a literal backtick (`) here.``
+ A single backtick in a code span: `` ` ``
  A backtick-delimited string in a code span: `` `foo` ``

### 图片
- ![Dropbox](https://dt8kf6553cww8.cloudfront.net/static/images/icons/blue_dropbox_glyph-vflJ8-C5d.png "dropbox")
- ![Google][google]
- ![Google][google]

### 自动连接
<http://www.bing.com>
## Create By

> Written with [StackEdit](https://stackedit.io/).


  [google]: https://www.google.com/images/srpr/logo11w.png "google"
  [1]: https://www.google.com "google"
  [2]: https://twitter.com "twitter"