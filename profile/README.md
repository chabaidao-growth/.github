# chabaidao-growth · 增长产品部

Claude Code Skill + PRD / 原型协作机制的中心化代码托管 Org。

PM 在 Claude Code 中用自然语言驱动 AI，生成符合公司设计规范的高保真原型 + 维护 PRD 与原型的版本对齐。

---

## 🎨 当前 Skill 清单

| Skill | 能力 | Owner | 版本 |
|---|---|---|---|
| [`ux-helper`](https://github.com/chabaidao-growth/ux-helper) | 轻量级 antd 设计规范 / 原型生成 | 雷斯岸（UX 设计师） | v0.5.0 |
| [`prd-review-kit`](https://github.com/chabaidao-growth/prd-review-kit) | PRD 文档审查 | 刘雨婷 | v0.5.0 |

---

## ⚡ Skill 装载

在产品工程仓终端执行：

```bash
# 装 UX 助手
npx --yes ux-helper@github:chabaidao-growth/ux-helper#v0.5.0 init
```

```bash
# 装 PRD 审核 Skill
npx --yes prd-review-kit@github:chabaidao-growth/prd-review-kit#v0.5.0
```

通用语法：

```
npx --yes <skill>@github:chabaidao-growth/<repo>#vX.Y.Z
```

> 💡 首次安装前需让 git 能拉 `chabaidao-growth` 的 private 仓——执行人 `gh auth login`。

---

## 📖 治理文档

- 🔗 飞书汇报文档：[Skill 维护 Product/macro 维护 PDD](https://www.feishu.cn/docx/AremdZPRvot1AixkY6bcdExfn7g)

---

## 🏆 Skill 治理流程

| 角色 | 职责 |
|---|---|
| 🧑‍💻 Skill Owner | 维护 Skill 的 Skill 迭代 + PRD 维护（GitHub Release + tag同步） + 飞书版本对齐 |
| Org Admin（管理者） | Org 级别 Skill 评审 + 审批 Skill 版本发布 + 飞书版本对齐 |

---

## 📢 Skill 共建

我们欢迎团队成员共建 Skill：

- 🔸 贡献方式 1：在 `prd-review-kit` skill 上提 issue/pr，或在 Skill 仓库提 issue/pr
- 🔸 贡献方式 2：参与 `skill-builder` 社区共建，共同维护 Skill -> package.json -> go -> commit -> tags -> release

当前共建中的 Skill：[`ux-helper`](https://github.com/chabaidao-growth/ux-helper) | [`prd-review-kit`](https://github.com/chabaidao-growth/prd-review-kit)
