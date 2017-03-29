> 非常方便好用的静态文件服务器
##### 顾名思义，anywhere 就是可以在任何地方搭建静态文件服务器，非常简单，按照以下步骤轻松搞定


<ol>
   <li>npm install anywhere -g </li>
   <li>在你的静态文件夹中打开命令行</li>
   <li>输入 anywhere (使用默认端口号打开 8000)</li>
   <li style="list-style:none">自动打开默认浏览器，弹出页面</li>
</ol>

##### 以上只是简单使用，下面整理一些常用的命令

```javascript
	anywhere  //默认8000端口打开
	anywhere 8888 //使用8888端口号打开
	anywhere -p 8888 //使用8888端口号打开
	anywhere -s //只启动服务器，不打开浏览器
	anywhere -h localhost //localhost 作为主机名
	anywhere -d /home // /home 作为根
	anywhere -f /index.html  // 使用 html5 history模式打开，并指定打开index.html
```

觉得用着不错就给个小星星呗 :)
<a href="https://github.com/zzf88521/anywhere" aria-label="Homepage" class="site-footer-mark" title="Star Me">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
