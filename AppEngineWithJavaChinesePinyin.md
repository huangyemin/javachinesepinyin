# Introduction #

随着网络的发展，拼音输入法已经不应该仅仅用来帮助用户输入。例如使用云端输入法，能够在没有像google，百度那样的搜索引擎的情况下，也可以成为一个网络新词的获取手段，并最终成为自然语言处理应用的一大数据来源。在这样的意义的驱使下，将javachinesepinyin发布到appengine成为我们的第一个目标。


# Details #

首先选择的云计算平台是google appengine，这是因为这是一个简单实用的平台，但是AppEngine有关于上载文件的大小限制，目前我们仅仅上传了bigram的统计信息，下一步就是改进数据结构，希望能够上转更多，更大的统计数据。

访问appengine，请打开链接：
[http://951438.appspot.com/pinyin.jsp](http://951438.appspot.com/pinyin.jsp)