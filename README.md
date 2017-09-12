## 编译 [ECMAScript 6入门](https://github.com/ruanyf/es6tutorial):

1. 安装 gitbook 和 ebook-convert:

   ```shell
   npm -g install gitbook-cli
   # 安装 calibre，然后创建软连接
   ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin
   ```

2. 将 [ECMAScript 6入门](https://github.com/ruanyf/es6tutorial)将 [SUMMARY.md](#es6tutorial/SUMMARY.md) 克隆到本地，然后将 [SUMMARY.md](#es6tutorial/SUMMARY.md) 拷贝到 [ECMAScript 6入门](https://github.com/ruanyf/es6tutorial) 根目录，执行命令生成相应的电子文档：

   ```Shell
   gitbook build
   gitbook pdf/epub/mobi
   ```

   ​

