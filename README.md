# find-them

这个小项目是为了从知乎的众多答案数据中找到我们想要的数据。

https://www.zhihu.com/question/275359100

此为知乎问题“你的择偶标准是怎样的”的链接，目前已超过两万余条回答，俨然成为知乎上最大最热的相亲营地。
但由于知乎的搜索功能无法满足对某些关键字的二次搜索，比如地域的搜索。
这就导致我们如果想要搜索两万条回答中，有关“西安”的信息，我们就几乎无从下手。（至少我没发现什么有效办法）。

于是乎，本着“让大家尽快找到自己满意的另一半”的出发点^-^，我就开发了这个小型爬虫，以满足大家对地域，或者其它关键字的搜索需求。

由于近期较忙，而且还在筹备自己的个人网站(没有用现成的解决方案，计划自己用Java框架开发，进度比较慢)，所以这个爬虫暂时只保证基本功能，算是个雏形吧。等随后一段时间忙完了，我会重新把这个爬虫完善，并且会做一个相对好看的ui，放在我的小站中。

目前访问形式：http://106.13.37.108
个站地址 www.becto.cn （备案中，清大家先用上述ip地址访问）

自己做这个爬虫纯粹是为了方便大家。所以为避免一些不必要的麻烦，我个站中的爬虫，只针对“你的择偶标准是怎样的”这一个问题，所以我就把搜索链接写死了。
如果有涉及到一些敏感信息，请知情朋友告知我，我会第一时间做出处理。


本人水平有限，欢迎大家的意见和建议。


版本规划：

version1.0

仅支持按发布/修改间排排序，最近500条的知乎回答。

后续会加入内容：

加入solr搜索引擎，使用搜索引擎进行搜索，支持搜索关键字高亮显示
将所有两万余条回答全部加入搜索引擎
待定
