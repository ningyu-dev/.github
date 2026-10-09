# .github

组织元仓库。不放产品代码，只承载整个组织的「门面」与默认配置。

## 目录结构

```
.github/
├── README.md              # 本文件：仓库自身说明（仅在本仓库页面可见）
├── NOTICE.md              # 规范原文版权边界说明
└── profile/
    └── README.md          # 组织主页内容，渲染在 github.com/ningyu-dev 顶部
```

## 如何更新组织主页

编辑 `profile/README.md`，提交并推送到默认分支。刷新组织首页即可看到更新，通常即时生效。

注意：**只有 `profile/README.md` 会渲染到组织主页**，根目录的 README 不会。如果改了根目录 README 发现主页没变化，就说明文件放错位置了。

## 其他可用能力

`.github` 仓库还能集中托管组织级默认文件，会被同组织下所有仓库继承：

- `CONTRIBUTING.md` — 贡献指南
- `CODE_OF_CONDUCT.md` — 行为准则
- `SECURITY.md` — 安全漏洞报告方式
- `config/` — 组织级配置

当前项目规模很小，暂不需要配置这些。等有协作者时再加。
