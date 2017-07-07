前端面试题
[js](#js)
[css](#css)
[html](#html)

### js

### css

- 1、页面导入样式时，使用link和@import有什么区别
   - 1、link属于xhtml标签，@import是css2.1提出的。@import只能加载css，而link除了加载css，还可以定义rel连接属性，RSS等。
   - 2、加载顺序的差别。@import引用的css会等到页面全部下载完再被加载，link引用的css在文件加载时，css已经可以渲染了
   - 3、@import的css不可以使用dom控制样式
   - 4、兼容性问题，ie5+才识别@import，其实也算没有兼容问题
### html
