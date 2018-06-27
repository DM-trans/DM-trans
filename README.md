# 《数据挖掘》教材翻译
欢迎来到《数据挖掘》教材翻译的repo.

《Data Mining》一书由Charu C.Aggarwal所著，出版于2015年4月14日，目前没有引进中国，亚马逊原版教材售价约为350元（会员价，非会员1000+）。豆瓣无评分，亚马逊评分4星（5星满分），从CSDN社区一些讨论情况来看，普遍认为本书质量较高。故我们选取本书进行翻译，旨在帮助更多中国学习者阅读优秀教材。

全书共有20章，743页，内容详细，逻辑严谨，其中包含大量图表与公式。

本repo是由NUDT的现代模式识别课程的学生，在课程作业之余的顺手而为。分工方案见[前期准备](https://liyaolife.com/data-mining翻译前期准备/)。


## How to build？

本文档目前采用 [mkdocs](https://github.com/mkdocs/mkdocs) 部署在 [https://dm-trans.github.io/DM-trans/](https://dm-trans.github.io/DM-trans/)。当然也可以部署在本地，具体方式如下：

### 安装依赖

```shell
# mkdocs
pip install mkdocs
# extensions
pip install pymdown-extensions
# theme
pip install mkdocs-material
```

### 本地部署

```shell
# generate static file in site/
mkdocs build
# deploy at http://127.0.0.1:8000
mkdocs serve
```

**mkdocs 本地部署的网站是动态更新的，即当你修改并保存 md 文件后，刷新页面就能随之动态更新。**


欢迎大家帮助我们完善！



