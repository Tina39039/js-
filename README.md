# js-一键复制
* 一个小小的deme
>
1.首先引入clipboard.js;
>
2.html内容：
>
` <p>随机密码<span id="password"></span><input id="copyPassword" type="button" data-clipboard-target="#password" value="一键复制"></p>`
>
3.js
>
` new Clipboard("#copyPassword");`
>
ok，一键复制功能就成功啦~

  
