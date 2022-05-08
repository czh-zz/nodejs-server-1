<h1>启动应用</h1>
  <p>node server.js 8888<p>
  <p>或者<p>
  <p>node server 8888<p>
 <h1>添加路由</h1>
 <ol>
  <li>编辑server.js，添加else if</li>
  <li>重新运行node.js</li>
</ol>
<h1>后台启动应用</h1>
touch log server.js 8888 >log log 2>&1 &
