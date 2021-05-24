# tool

二、离线安装 VSCode 插件

接下来，我来总结下 VSCode 插件离线安装的步骤：

1. 打开 VSCode 插件市场网址 Extensions for the Visual Studio family of product，输入你想要的插件名称，比如这里我想要安装的是 Markdown All in One 插件


2. 点击进入插件主页，点击右侧的 Download Extension 链接，得到下载下来的离线安装包，以 .vsix 为扩展名结尾


3. 把下载下来的离线安装包拷贝到 VSCode 的安装目录下的 bin 目录下，比如我的 VSCode 安装在 D:\Microsoft VS Code\，因此这里我应该拷贝到 D:\Microsoft VS Code\bin 这个目录下

4. 在第 3 步的 bin 目录下右键点击 在此处打开命令窗口，输入命令，最后面的参数换成你下载的插件离线安装包的名字即可：

code --install-extension yzhang.markdown-all-in-one-1.4.0.vsix

    1

待看到如下提示即意味着安装成功，就可以打开 VSCode 进行查看了

    Extension ‘yzhang.markdown-all-in-one-1.4.0.vsix’ was successfully installed!

至此，离线安装 VSCode 插件就算结束了 _

