## Github特殊的Markdown格式

通过`<kbd></kbd>`来描述按钮

按<kbd>t</kbd>进入搜索

颜色描述: `#C6E48B` `#7AC96F` `#249A3C` `#1589F0`

- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `#f03c15`
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `#c5f015`
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `#1589F0`

代码差异对比：

```diff
10 PRINT “BASIC IS COOL”
- 20 GOTO 11
+ 20 GOTO 10
```

展示细节

<details>
<summary>这里有很多细节，展开后显示</summary>
<pre>
细节
细节
细节
很多细节


居中图片与文字
`<div align=”center”> [ Your content here ]</div>`

<div align="center">
<img src="https://octodex.github.com/images/dunetocat.png" width="200">
<p>居中的图片与文字</p>
</div>


创建较小的文字`<sup> or <sub>`

<div align="center">
<img src="https://octodex.github.com/images/megacat-2.png" width="200"><br>
<sup><strong>加粗+较小</strong> 较小文字</sup>
</div>
View more octocats on the [Octodex](https://octodex.github.com/)!