# Github API V3 翻译计划



## 一.翻译说明

[Github API V3](https://developer.github.com/v3/) 提供非常多的功能，文档翻译也是熟悉这些API的过程，希望可以帮助更多人发挥创意制作有趣的产品。



### 后续维护计划

官方文档会持续更新，我们也会不定期检查更新。



## 二. 开始翻译

### 加入翻译

想贡献翻译的同学可以Fork[https://github.com/CloudCrystal/github-api-v3](https://github.com/CloudCrystal/github-api-v3) ，然后开新的分支，提交PR。

### 领取翻译

在[issus](https://github.com/CloudCrystal/github-api-v3/issues/1)下留言领取任务，留言内容如：

> 我要认领翻译 「活动 ->订阅（Activity -> Feed）」

### 翻译规范

我们严格遵循[中文排版指南](https://github.com/sparanoid/chinese-copywriting-guidelines)

- 英文的左右 **必须** 保持一个空白，避免中英文字黏在一起；
- **必须** 使用全角标点符号；
- **必须** 严格遵循 Markdown 语法；
- 原文中的双引号（" "）请代换成中文的引号（「」符号怎么打出来见 [这里](http://zhihu.com/question/19755746/answer/27233392)）；
- 「`加亮`」和「**加粗**」和「[链接]()」都需要在左右保持一个空格。

### 文件结构

- `src` 源目录
- `src/{章节目录}`
- `src/{章节目录}/翻译文件名.md`

例如：

```
└── src
    └── activity
            └── activity.md
```



> Fork 项目至你的仓库，根据认领的章节或小节建立文件夹、新建文件、添加翻译文件。



## 三. 翻译署名

翻译参与者对译文能行使署名权，就如画家在作品上签名。

例如，以下 Markdown 代码会在文档最底部出现：

```
## 译者署名
| 用户名 | 贡献 | 签名 |
| --- | --- | --- | --- |
| [@starriv](https://github.com/starriv) |  翻译 [Gists](https://developer.github.com/v3/gists/)  | Web Developer |
| [@Tom](https://github.com/V-Tom) |  翻译 [Activity](https://developer.github.com/v3/activity/)  | Node && FE Developer |
```


解析后为：

| 用户名                                    | 贡献                                       | 签名                   |
| -------------------------------------- | ---------------------------------------- | -------------------- |
| [@starriv](https://github.com/starriv) | 翻译 [Gists](https://developer.github.com/v3/gists/) | Web Developer        |
| [@Tom](https://github.com/V-Tom)       | 翻译 [Activity](https://developer.github.com/v3/activity/) | Node && FE Developer |