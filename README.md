# 使用方法

1. 下载代码 `git@github.com:linkzhangithub/kuayu-1.git`
2. 进入 qq-com 运行 server.js `cd kuayu-1/qq-com; node server.js 8888`
3. 进入 link-com 运行 server.js `cd ../link-com; node server.js 9999`
4. 找到系统文件并设置host：
```
127.0.0.1 qq.com
127.0.0.1 link.com
```
5. 打开两个页面 qq.com:8888/index.html 和 link.com:9999/index.html
6. 做完后要删除 host 文件里的两行设置，否则qq.com无法正常访问
