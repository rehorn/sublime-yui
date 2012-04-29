Yui Compressor for Sublime Text 2 本地版简介
========================
Yui Compressor for Sublime Text 2 是代码编辑器Sublime Text 2的一个Css编译插件，能够对Css进行压缩，生成用于生产环境的.min.css文件。

安装
========================
* 方式1
    * 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
    * 在Packages目录本代码仓库，Git Clone https://github.com/rehorn/sublime-yui
    * 打开一个css文件，按F7或Ctrl+b，在同级目录下生成.min.css文件
* 方式2
    * 安装 Packages Control 后，将本代码仓库添加到源
        * ctrl+alt+p之后，输入add repository，输入https://github.com/rehorn/sublime-yui
    * 执行 Packages Control 后，就能搜索到 sublime-yui ，安装即可
    * 打开一个css文件，按F7或Ctrl+b，在同级目录下生成.min.css文件

使用
========================
* 打开一个css文件，按F7或Ctrl+b，在同级目录下生成.min.css文件

自定义
========================
* 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
* 进入sublime-yui
* 修改YUI Compressor.sublime-build文件，可以自定义编译目录，文件名等
* 可替换complier/yuicompressor-2.4.7.jar升级yuicompressor

其他
========================
* 网络环境较好用户可以使用在线版 https://github.com/leon/YUI-Compressor
* 本版本为满足离线网络环境的开发


