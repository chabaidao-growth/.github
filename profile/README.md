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

## 🧪 当前产品原型仓

按 PRD ↔ 原型版本协作机制托管的产品工程仓（每个仓含 `PRD.md` + `PRD-LINKS.md` 桥接表 + GitHub Pages 在线预览）。

| 产品 | 在线预览 | PRD 飞书链接 | Owner | 当前 tag |
|---|---|---|---|---|
| [`recommend-admin-prototype`](https://github.com/chabaidao-growth/recommend-admin-prototype)<br>推荐系统运营管理后台 | [Pages 预览](https://chabaidao-growth.github.io/recommend-admin-prototype/) | [PRD v3.3](https://swn7zpxv453.feishu.cn/docx/GCBXdFXtboAMk2xoPIPcB6uRnSf) | 何旭 | `v1.0` |

> 仓库 Topic 用 `prd` 标识产品工程仓。后续接入更多业务产品（如冯遂舟试用产品）后会在此表追加。

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

> 💡 首次安装前需让 git 能拉 `chabaidao-growth` 的 private 仓——执行一次 `gh auth login` 即可。

---

## 📖 治理文档

- 🔗 飞书汇报文档：[Skill 管理 & PRD 协作机制](https://swn7zpxv453.feishu.cn/wiki/HlpcwmiRLiR6OPkldEZcQ4fhnEd)

---

## 🏆 治理流程

| 角色 | 职责 |
|---|---|
| 🧑‍💻 Skill Owner | 维护 Skill 骨架 + 发版（GitHub Release + tag）+ 同步飞书版本对齐 |
| 🧰 产品仓 Maintainer | 维护 `PRD.md` + `PRD-LINKS.md` + 飞书 PRD 双向同步 + 每次迭代发 GitHub Release |
| Org Admin（管理者） | Org 级别评审 + 审批版本发布 + 维护本 README 清单 |

---

## 📢 共建

我们欢迎团队成员共建：

- 🔸 **贡献 Skill**：在已有 Skill 仓提 issue/pr，或参与 `skill-builder` 社区共建
- 🔸 **接入产品**：联系 Org Admin 创建产品工程仓，引入 PRD-LINKS 桥接机制

当前共建中：[`ux-helper`](https://github.com/chabaidao-growth/ux-helper) · [`prd-review-kit`](https://github.com/chabaidao-growth/prd-review-kit) · [`recommend-admin-prototype`](https://github.com/chabaidao-growth/recommend-admin-prototype)
