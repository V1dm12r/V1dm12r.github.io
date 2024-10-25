1. _config.yml

    作用：全局配置文件，包含网站的基本信息和设置，如标题、描述、URL 等。

2. _layouts

    作用：存放布局模板，定义页面的整体结构和样式，允许不同页面复用相同布局。

3. _includes

    作用：存放可复用的 HTML 片段，例如导航栏、页脚等，便于在布局或页面中引入。

4. _posts

    作用：存放博客文章，每篇文章以日期为前缀命名，格式为 YYYY-MM-DD-title.md，Jekyll 会根据这些文件生成博客列表。

5. _data

    作用：存放 YAML、JSON 或 CSV 格式的数据文件，可以在页面和模板中引用，适用于需要多次使用的数据。

6. _assets 或 assets

    作用：存放静态资源，如 CSS、JavaScript 和图片等，通常在 _layouts 和其他文件中引用。

7. _plugins

    作用：存放自定义的插件，扩展 Jekyll 的功能，通常是 Ruby 代码。

8. _drafts

    作用：存放草稿文章，未发布的文章不会出现在博客中，草稿文件以 .md 结尾，命名不需要日期前缀。

9. index.html 或 index.md

    作用：网站的首页，通常用于定义主页的内容和布局。

10. 其他文件

    作用：其他文件和文件夹可以包含静态页面、文档、许可证等，按照需要组织。
