# pdfjs_demo
+pdfjs的github源码地址：https://github.com/mozilla/pdf.js
+pdf js的简略版本demo。 
+直接访问服务器地址/pdfjs_demo/可以看到嵌入了pdfjs的网页 
然后更改index.jsp的iframe的src地址 例如：<iframe id="pdfjscontainer" src="pdfjs/web/viewer.html?file=compressed.tracemonkey-pldi-09.pdf" style="height: 450px;width: 100%"></iframe> 
+需要关心的是。我现在file地址指的pdfjs/web/里的compressed.tracemonkey-pldi-09.pdf
+也可以直接访问服务器址/pdfjs_demo/pdfjs/web/viewer.html?file=xxx xxx为文件名。
+可以加载远程服务器的文件。但是我还没调试好。先这样吧