
<!---

此README是从这些文件中的注释自动生成的：
prism-highlighter.html

编辑这些文件，我们的readme bot将在这里复制它们！
编辑此文件，机器人将压缩您的更改:)

机器人做一些处理markdown。 如果错误，请提交错误
事情! https://github.com/PolymerLabs/tedium/issues

-->


##&lt;prism-highlighter&gt;

语法高亮通过 [Prism](http://prismjs.com/).

在文档中放置一个`<prism-highlighter>`，最好是
`<body>`。 它将监听其父元素上的`syntax-highlight`事件，
并注释通过该事件提供的代码.

`syntax-highlight`事件的细节应该有一个`code`属性
包含要突出显示的源。 事件详细信息可以选择性地包含a
`lang`属性，包含一个字符串，如“html”，“js”`等.

支持此流程 [`<marked-element>`](https://github.com/PolymerElements/marked-element).


