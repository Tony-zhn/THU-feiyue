---
# hide:
#   - navigation
#   - toc
comments: true
---

# 清华大学飞跃手册

!!! info "进度与更新"

    已经完成了大部分 [前言](preface), [准备](prepare) 部分内容。

    由于笔者经历有限、能力有限，不知道的不能胡说，没有的就是不知道。所以我们希望有更多同学帮助撰写和完善网站内容。

    计划于 6 月底之前完成申请常识、部分前期准备；8 月底申请季之前完成大部分申请准备和个人经验总结 / 案例。

## 关于

[清华大学飞跃手册](https://feiyue.online)（简称“手册”）是由一群清华大学出国（境）深造的毕业生编写维护的在线文档。

该手册旨在总结出国（境）深造的经验教训，分享个人申请案例故事，为拟出国（境）深造的学弟学妹提供借鉴和参考，减少信息差带来的不公平，降低准备时间和金钱成本，缓解申请过程中的焦虑。

希望本手册能够帮助到拟出国（境）深造的清华学生，在申请路上顺顺利利，获得自己心仪项目的 Offer！




## 读者须知

手册内容基本按照申请过程的时间顺序编排；案例由编委会收集，来自于往届毕业生个人贡献。本手册的章节结构如下：

- [首页](../)：本手册基本信息、友链。
- [前言](preface/why/)：关于为什么留学深造、如何选择项目和收集信息等的综述。
- [准备](prepare)：决定申请后需要实施的行动和方法。
- [录取及之后](afterad)：收到结果后需要做的事情。
- [案例](cases)：包括清华大学各年级各专业毕业生的个人背景和故事分享，以供参考。
- [招生信息](ad)：包括一些项目或课题组的招生广告、要求和指引。
- [联系与支持](contact/support/)：本手册的贡献者，合作和支持的相关信息。

!!! note "站内导航"
    -   （PC端）可以通过点击页面页眉位置的横向导航条前往不同的章节。章节内部有若干主题的帖子，选择你感兴趣的浏览即可，可以通过页面右侧的目录栏快速定位到页面指定位置。
    -   （移动端）可以通过页面左上角的导航栏按钮 :fontawesome-solid-bars: 再点击一次 :material-arrow-left: 以回到主菜单，前往不同的章节。可以通过页面左上角导航栏按钮 :fontawesome-solid-bars: + 页面标题右侧的目录按钮 :material-table-of-contents: 浏览目录快速定位到页面指定位置。

如果需要快速检索一些词条内容，可以使用页面右上角的搜索功能。英文搜索可以丝滑进行；中文搜索请以两个字组词为单位断词，例如要搜索 `北京大学` 应该键入 `北京` `大学`。可以搜索 [案例 tag](cases/tags) 来快速寻找特定特色的案例帖。

如果浏览过程中遇到想要发问的，或是有自己的见解要发表，或是进行简单的勘误，可以在 [QA](main/qa/) 中页面底部的评论区发帖，我们会将实用问题总结出来发布。

本手册的内容均由往届的申请者们的个人经验汇总而成，请读者一定注意这些信息多少具有个人色彩，并留心甄别时效性。在规划自己的申请时请一定结合自身情况和时代背景进行。

> 一个人的命运啊，当然要靠自我奋斗，但是也考虑到历史的行程。

随着申请飞跃一年年进行，我们也希望有更多读者为飞跃手册贡献内容，留下宝贵的申请记录，让这份飞跃手册能够持续为同学们提供最新的申请支持。

## 声明

本手册使用 [Material for Mkdocs](https://squidfunk.github.io/mkdocs-material/) 构建，在 [GitHub](https://github.com/THU-feiyue/THU-feiyue) 上开源，使用 GitHub Pages 公开发布。

手册内容由清华大学飞跃手册编写委员会收集、编写、审核、发布并维护。内容仅供参考，且不代表任何政治立场。手册所有内容 **不得做商业用途，转载或者引用请注明来源**。

对于不遵守此声明或者其他违法使用本文内容者，依法保留追究权等。


## 贡献

### Github PR

您可以直接通过 Github Pull Request 的方式为本项目贡献。不管是为说明指引部分撰写知识还是发布案例，直接 Github PR 都是比较方便的方式，在本项目的 [GitHub](https://github.com/THU-feiyue/THU-feiyue) 页面中 fork 到自己的库，修改后再提交 PR，我们会在检查通过后发布在页面内。

如果您计划直接以网页的形式发布你的案例信息，只需要做如下四步，就像把大象塞进冰箱一样：

1.  从本项目的 [GitHub](https://github.com/THU-feiyue/THU-feiyue) 页面中 fork 到自己的库，开始进行编写；
2.  自行编写好渲染所需的 `.md` 文件后，放在 `./docs/cases/<year of ad>` 目录下（或是对已有页面进行修改）。案例的具体内容建议可见 [案例模板](cases/example)，此文件在项目中路径为 `./docs/cases/example.md`；
3.  在 `./mkdocs.yml` 文件中的 `nav:` 部分维护网站导航结构，以确保你的帖子能在网站目录中 access 到；
4.  提交并推送你的更改到自己的库，然后在 Github 中创建 Pull Request。

排版的技术内容可以参考 [Material for Mkdocs 的文档](https://squidfunk.github.io/mkdocs-material/)，排版建议可见相似网站的创作者指引，如 [OI WIki](https://oi-wiki.org/intro/format/) 和 [贵系](https://docs.net9.org/notes/editor/) 的文档。

### 邮件

如果您不习惯于使用 Github 或者是不喜欢 `.md` 语言格式，可以直接以你习惯的文档形式（any, e.g. `.txt` / word `.docx` / `.pdf`）将帖子发送到邮箱：<mailto:contact@feiyue.online>，手册的维护人员会联系您并为网页排版和组织提供帮助。

### 页面评论区

我们在本页面和 [QA](main/qa/) 页面底部放置了评论区，可以在其中提出简短的更新或勘误。