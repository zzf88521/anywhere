>非常方便好用的静态文件服务器
#####顾名思义，anywhere就是可以在任何地方搭建静态文件服务器，非常简单，按照以下步骤轻松搞定

<ol>
	<li>npm install anywhere -g </li>
   <li>在你的静态文件夹中打开命令行</li>
   <li>输入 anywhere (使用默认端口号打开 8000)</li>
   <li style="list-style:none">自动打开默认浏览器，弹出页面</li>
</ol>

#####以上只是简单使用，下面整理一些常用的命令

```javascript
	anywhere  //默认8000端口打开
	anywhere 8888 //使用8888端口号打开
	anywhere -p 8888 //使用8888端口号打开
	anywhere -s //只启动服务器，不打开浏览器
	anywhere -h localhost //localhost 作为主机名
	anywhere -d /home // /home 作为根
	anywhere -f /index.html  // 使用 html5 history模式打开，并指定打开index.html
```

觉得用着不错就给个小星星呗，: )
