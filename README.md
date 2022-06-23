# 开发扩展kafka插件

* datax基于Framework + plugin架构构建。将数据源读取和写入抽象成为Reader/Writer插件，开发者可以通过扩展开发Reader/Writer实现自己公司多源数据同步需求。

* 本项目主要将kafka插件扩展进去，将公司数据实现星型数据链路数据平台，DataX作为中间传输载体负责连接各种数据源。当需要接入一个新的数据源的时候，只需要将此数据源对接到DataX，便能跟已有的数据源做到无缝数据。
* 类图
![dataX流程图](https://user-images.githubusercontent.com/55180060/175015683-00c1c65e-7bae-4973-a552-f52d7c3f806c.png)
