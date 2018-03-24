# 第2章 模块机制

模块化结构

Node 实现 CommonJS 规范，所以可以使用模块化的方式组织代码结构

## 核心模块的意义

- 如果只是在服务器运行JavaScript代码，意义并不大，因为无法实现任何功能（读写文件，访问网络）。
- Node 的用处在于它本身还提供的一系列功能模块，用于与操作系统互动。
- 这些核心的功能模块在 Node 中内置。


## 内置如下模块：

- [path](http://nodejs.org/api/path.html)：处理文件路径。
- [fs](http://nodejs.org/api/fs.html)：操作文件系统。
- [child_process](http://nodejs.org/api/child_process.html)：新建子进程。
- [util](http://nodejs.org/api/util.html)：提供一系列实用小工具。
- [http](http://nodejs.org/api/http.html)：提供HTTP服务器功能。
- [url](http://nodejs.org/api/url.html)：用于解析URL。
- [querystring](http://nodejs.org/api/querystring.html)：解析URL中的查询字符串。
- [crypto](http://nodejs.org/api/crypto.html)：提供加密和解密功能。
- [其他](https://nodejs.org/api/)

















