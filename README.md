https://github.com/zhangsuo/ZSUnusedResource/blob/master/LSUnusedResourcesExample.gif

##用法

它是一个有用的实用工具，可以检查Xcode项目中没有使用哪些资源。非常容易使用：

1.单击“浏览…”选择一个项目文件夹。
2.单击“搜索”开始搜索。
3.等待几秒钟，结果将显示在tableview中。

##特征

选中“忽略相似名称”以忽略字符串连接引用的资源

##工作原理

1.在这些文件夹“[imageset，launchimage，appiconset，bundle，png]”中获取资源文件（默认值：“[imageset，jpg，png，gif]”）。
2.使用正则表达式搜索代码文件中的所有字符串名称（默认值：`[h、m、mm、swift、xib、故事板、字符串、c、cpp、html、js、json、plist、css]`）。
3.从资源文件中排除所有使用的字符串名称，我们得到所有未使用的资源文件。

##要求

需要OS X 10.7及以上版本，ARC。
