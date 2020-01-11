# 为 Thenx CMS 做贡献
      **Thenx CMS**  是根据Apache 2.0许可发布的。如果您想贡献代码或者文档，那么本文档应该可以帮助您入门。

# 行为守则
      该项目遵守《贡献者公约》[行为守则](https://github.com/thenx-projects/thenx-cms/blob/master/CODE_OF_CONDUCT.md)。通过参与，您将遵守此代码。请向 thenx-wei@thenx.org 报告不可接受的行为。

# 使用GitHub问题
我们使用GitHub问题来跟踪错误和增强功能。如果您有一般用法问题，请在Stack Overflow上提问。Spring Boot团队和更广泛的社区监视该spring-boot 标签。

如果您正在报告错误，请通过提供尽可能多的信息来帮助加快问题诊断。理想情况下，这将包括一个重现问题的小样本项目。

报告安全漏洞
如果您认为自己在Spring Boot中发现了安全漏洞，请 在我们有机会对其进行修复之前不要公开披露该漏洞。请不要使用GitHub问题报告安全漏洞，而请转到https://pivotal.io/security并了解如何以负责任的方式披露这些漏洞。

签署贡献者许可协议
在我们接受不重要的补丁或请求请求之前，我们将需要您 签署“贡献者许可协议”。签署贡献者协议并不会授予任何人对主存储库的提交权，但这确实意味着我们可以接受您的贡献，并且如果您这样做，您将获得作者的荣誉。可能需要活跃的贡献者加入核心团队，并具有合并合并请求的能力。

规范和内务守则
这些对于拉取请求都不是必不可少的，但它们都会有所帮助。也可以在原始请求请求之后但在合并之前添加它们。

我们使用Spring JavaFormat项目来应用代码格式约定。如果您使用Eclipse，并且按照下面的“导入到Eclipse中”说明进行操作，则应该自动获取特定于项目的格式。您还可以安装 Spring JavaFormat IntelliJ插件或通过运行来构建Gradle构建中的代码格式 ./gradlew format。

该构建包括许多代码约定的Checkstyle规则。./gradlew checkstyleMain checkstyleTest如果要检查更改是否符合要求，请运行 。

确保所有新.java文件都具有简单的Javadoc类注释，其中至少包含一个@author用于标识您的 标签，并且最好至少包含有关该类用途的段落。

将ASF许可证标头注释添加到所有新.java文件（从项目中的现有文件复制）

将您自己添加为@author要进行.java实质性修改的文件（不仅仅是外观更改）。

添加一些Javadocs。

进行一些单元测试也有很大帮助-有人必须这样做。

如果没有其他人在使用您的分支，请根据当前的主节点（或主项目中的其他目标分支）对其进行重新设置。

编写提交消息时，请遵循以下约定，如果要解决现有问题，请Fixes gh-XXXX在提交消息的末尾添加（XXXX发行号）。

使用守则
如果您没有IDE偏好设置，我们建议您在使用代码时使用 Spring Tools Suite或 Eclipse。我们将 Buildship Eclipse插件用于Gradle支持。其他IDE和工具也应该可以正常工作。
