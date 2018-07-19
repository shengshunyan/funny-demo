---
title: HTML语义化
date: 2018-06-03
categories: "HTML语义化"
tags: 
     - HTML
---
写可读性更高的HTML代码！
*reference: https://blog.csdn.net/coco379/article/details/52938071*

## 1. 优点
1. 提升可访问性；
2. SEO；
3. 结构清晰，利于维护；

<!-- more -->

## 2. 通用容器
    ```
    div --- 快级通用容器
    span --- 短语内容无语义容器
    ```
## 3. 语义化标签
    ```
    <!-- 结构 -->
    <title></title>：简短、描述性、唯一（提升搜索引擎排名）。

    <header></header>：页眉通常包括网站标志、主导航、全站链接以及搜索框。

    <main></main>：页面主要内容，一个页面只能使用一次。如果是web应用，则包围其主要功能。

    <footer></footer>：页脚，只有当父级是body时，才是整个页面的页脚。


    <!-- mian -->
    <hn></hn>：h1~h6分级标题，用于创建页面信息的层级关系。

    <nav></nav>：标记导航，仅对文档中重要的链接群使用。

    <section></section>：具有相似主题的一组内容，比如网站的主页可以分成介绍、新闻条目、联系信息等条块。

    <li></li>: 列表元素。

    <address></address>：作者、相关人士或组织的联系信息（电子邮件地址、指向联系信息页的链接）。

    <code></code>：标记代码。包含示例代码或者文件名 （< &lt;  > &gt;）

    <pre></pre>：预格式化文本。保留文本固有的换行和空格。

    <meter></meter>：表示分数的值或者已知范围的测量结果。如投票结果。（静态）

    <progress></progress>：完成进度。可通过js动态更新value。（动态）


    <!-- 少用 -->
    <mark></mark>：突出显示文本（yellow），提醒读者。

    <small></small>：指定细则，输入免责声明、注解、署名、版权。

    <em></em>：标记内容着重点（大量用于提升段落文本语义）。

    <aside></aside>：指定附注栏，包括引述、侧栏、指向文章的一组链接、广告、友情链接、相关产品列表等。

    <cite></cite>：指明引用或者参考，如图书的标题，歌曲、电影、等的名称，演唱会、音乐会、规范、报纸、或法律文件等。

    <blockquoto></blockquoto>：引述文本，默认新的一行显示。

    <time></time>：标记时间。datetime属性遵循特定格式，如果忽略此属性，文本内容必须是合法的日期或者时间格式。     

    <dfn></dfn>：定义术语元素，与定义必须紧挨着，可以在描述列表dl元素中使用。

    ```