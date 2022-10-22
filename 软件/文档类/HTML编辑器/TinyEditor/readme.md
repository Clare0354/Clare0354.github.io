##### TinyEditor

在线编辑软件：[lipten.link/demo/editor/](http://lipten.link/demo/editor/)

参考：[TinyEditor:简洁且易用的html所见即所得编辑器 - phpStudy (xp.cn)](https://www.xp.cn/b.php/3451.html)

github：[umpox/TinyEditor: A functional HTML/CSS/JS editor in less than 400 bytes (github.com)](https://github.com/umpox/TinyEditor)

使用时在浏览器地址栏输入以下内容即可：

```html
data:text/html,<body oninput="i.srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'</script>'"><style>textarea,iframe{width:100%;height:50%}body{margin:0}textarea{width:33.33%;font-size:18}</style><textarea placeholder=HTML id=h></textarea><textarea placeholder=CSS id=c></textarea><textarea placeholder=JS id=j></textarea><iframe id=i>
```

示例：

<img src="C:\Users\DaiZikun\AppData\Roaming\Typora\typora-user-images\image-20221003213747298.png" alt="image-20221003213747298" style="zoom:50%;" />

