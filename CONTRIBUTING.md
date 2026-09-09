# Contributing

[English](#english) · [简体中文](#简体中文)

## English

### What belongs here

A benchmark, dataset, or archive that someone validating a social simulation could actually compare against. It must fit one of the three layers ([L1](README.md#l1-individual-fidelity), [L2](README.md#l2-interaction-and-social-intelligence), [L3](README.md#l3-emergent-macro-alignment)), or one of the supporting sections.

Not a fit: papers with no released artifact, general-purpose agent benchmarks with no social dimension, frameworks that ship no evaluation, and anything whose link does not resolve.

Your own work is welcome under exactly the same criteria.

### Entry format

One table row, three cells:

```
| [Name](link) · [code](link) | what you actually get | one sentence, no marketing |
```

- **Name** links to the paper or project page. Add ` · [code]` or ` · [dataset]` when those live elsewhere.
- Fill in **Data** carefully; this list exists for that column. Say whether real human comparison data is obtainable, and under what terms: `20 datasets, downloadable from HF`, `1,052 interviews (restricted access)`, `evaluation code only`. "Comprehensive benchmark" is not an answer.
- **Notes** is one sentence saying what this is good for or what it fails at. Write the number when there is one.

Keep rows within a section in a sensible order; there is no strict sort.

### Both languages

Entries live in [README.md](README.md) and [README.zh-CN.md](README.zh-CN.md), in the same order in both. Edit both if you can. **Submitting in one language only is fine** — say so in the PR and a maintainer will fill in the other.

### Before you open the PR

- Open every link you added.
- CI runs a link check on all Markdown; a PR with a dead link will fail.
- One PR per theme. A batch of related entries in one PR is fine; unrelated changes are not.

Contributions are released under [CC0-1.0](LICENSE), same as the rest of the list.

---

## 简体中文

### 什么该收

能被拿来当社会模拟验证对照物的基准、数据集或档案。必须能归进三层之一（[L1](README.zh-CN.md#l1-个体保真度)、[L2](README.zh-CN.md#l2-交互与社交智能)、[L3](README.zh-CN.md#l3-宏观涌现与现实对齐)），或归进后面的辅助分类。

不收：没有放出任何产物的论文、不带社会维度的通用 agent 基准、不含评测的框架，以及链接打不开的东西。

自己的工作可以提，标准完全一样。

### 条目格式

一行表格，三格：

```
| [名字](链接) · [代码](链接) | 到手的是什么 | 一句话，不要宣传语 |
```

- **名字**链到论文或项目页。代码、数据在别处的话，补 ` · [代码]`、` · [数据]`。
- **数据**这一列要认真填，这个列表就是为它存在的。写清楚能不能拿到真人对照数据、以什么条件拿：`20 个数据集，HF 可下`、`1052 人访谈（受限申请）`、`只有评测代码`。"全面的基准"不算回答。
- **说明**一句话，讲它适合验证什么、或者它在哪儿不行。有具体数字就写数字。

同一分类内顺序合理即可，没有强制排序规则。

### 两种语言

条目同时存在于 [README.md](README.md) 和 [README.zh-CN.md](README.zh-CN.md)，两边顺序保持一致。能改两边就都改。**只写一种语言也可以提** —— 在 PR 里说一声，维护者会补另一边。

### 提 PR 之前

- 你加的每个链接都自己点开看一遍。
- CI 会对所有 Markdown 跑链接巡检，有死链的 PR 会挂。
- 一个 PR 一个主题。一批相关条目放一个 PR 没问题，无关改动不要混进来。

贡献内容以 [CC0-1.0](LICENSE) 释出，与列表其余部分一致。
