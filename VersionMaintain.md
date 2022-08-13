# ProjectStandard
## 版本规范
本文档依照 [语义化版本2](https://semver.org/lang/zh-CN/) 进行修改规范

本项目开发应该依照本文档优先处理,如无解决方案参考语义化版本2

版本号应当为 X.Z.Y 格式

1.主版本号X 当你做了不兼容的 API 修改，

2.次版本号Y 当你做了向下兼容的功能性新增，

3.修订号  Z 当你做了向下兼容的问题修正。

## 开发流程
Dev->Alpha->Beta->RC->Unstable->Release->Stable->End of File

Dev       开发环境版本

Alpha     内部版本

Beta      测试版本

RC        预发布版本

Unstable  非稳定版本

Release   发布版本

Stable    文档版本

EOL       终止维护

Unstable以下不包括Unstable均为非公布版本

Unstable以上包括Unstable为公开版本 但是注意Unstable公开 但不应该被推送
# 版本规范-1
在Unstable以下等级版本不包括Unstable情况开发可以出现类似

1.0.0-alpha+001

1.0.0-rc+001

1.0.0-beta+exp.sha.5114f85 (必要时可以出现)

格式出现为 major.minor.patch-prerelease+buildmetadata

# 版本规范-2
Unstable版本         Y应该保证为奇数

Release&Stable版本   Y应该保证为偶数

# 维护长度
一般为 X.Z-1.Y 至 X.Z-1.Y 的RC以上版本保持稳定

至少保证Update&Note服务正常 以便更新服务

# 公布版本流程
开发版本->公布版本开发完成->测试迭代->Stable版本推送

(开发版本包括Unstable不应该被公布)
