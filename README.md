# 使用方法

0. 安装 node-dev
    `yarn global add node-dev`
1. 下载代码 
2. 进入 qq.com 运行 server.js
    `cd CORS-demo-1/qq-com; node-dev server.js 8888`
3. 进入 bd.com 运行 server.js
    `cd ../bd.com; node-dev server.js 9999`
4. 设置 hosts
    ```
    127.0.0.1 qq.com
    127.0.0.1 bd.com
    ```
5. 打开两个页面 qq.com:8888/index.html 和 bd.com:9999/index.html
6. 记得做完之后，删掉 hosts 里的两行，否则 qq.com 无法正常访问！
