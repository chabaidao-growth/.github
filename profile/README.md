# chabaidao-growth · 增长产品部

Claude Code Skill + PRD / 原型协作机制的中心化代码托管 Org。

PM 在 Claude Code 中用自然语言驱动 AI，生成符合公司设计规范的高保真原型 + 维护 PRD 与原型的版本对齐。

---

## 🎨 当前 Skill 清单

| Skill | 能力 | Owner | 版本 |
|---|---|---|---|
| [`ux-helper`](https://github.com/chabaidao-growth/ux-helper) | 轻量级 antd 设计规范 / 原型生成 | 雷斯岸（UX 设计师） | v0.5.0 |
| [`prd-review-kit`](https://github.com/chabaidao-growth/prd-review-kit) | PRD 文档审查 | 刘雨婷 | 即将上线 |

---

## ⚡ Skill 装载

在产品工程仓终端执行：

```bash
# 装 UX 助手
npx --yes ux-helper@github:chabaidao-growth/ux-helper#v0.5.0 init
```

通用语法：

```
npx --yes <skill>@github:chabaidao-growth/<repo>#vX.Y.Z init
```

> 💡 首次安装前需让 git 能拉 `chabaidao-growth` 的 private 仓——执行一次 `gh auth login`。

---

## 📖 治理文档

- 🔗 飞书汇报文档：[Skill 管理 & PRD 协作机制（汇报版）](https://www.feishu.cn/docx/AremdZPRvot1AixkY6bcdExfn7g)

---

## 👥 维护责任

| 谁 | 做什么 |
|---|---|
| 主 Skill Owner | 维护自家 Skill 仓 + 发版（GitHub Release + tag） + 在本清单更新自家那行 |
| Org Admin（何旭） | Org 框架维护 + 新 Skill 立项审核 + 兜底清单维护 |

---

> 后台约定：每个 Skill 仓打 GitHub Topic `pm-skill` 作为标记。
