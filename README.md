# .github

这是 **周目** 组织的门面仓库。里面放两类东西：

## 1. 组织首页

首页显示的内容来自 [`profile/README.md`](profile/README.md) —— 改那个文件就能改组织首页。

```
profile/
├── README.md     ← 组织首页内容
└── banner.png    ← 首页顶部的横幅
```

## 2. 全组织共用的文件

放在根目录，**组织下所有仓库自动继承**（仓库自己没写的话就用这里的）：

| 文件 | 作用 |
| --- | --- |
| `ISSUE_TEMPLATE/bug_report.yml` | 报 Bug 的表单（强制填版本号 / 平台 / 系统） |
| `ISSUE_TEMPLATE/feature_request.yml` | 提建议的表单 |
| `ISSUE_TEMPLATE/config.yml` | issue 页面的入口链接 |
| `PULL_REQUEST_TEMPLATE.md` | PR 模板（含 iOS + watchOS 双平台自测项） |
| `SECURITY.md` | 安全策略（私密漏洞报告入口） |
