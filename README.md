<div align="center">

# pz-forge

**把不顺手的软件拆开、改顺，再放出来。**

[![Repos](https://img.shields.io/github/repo-count/pz-forge?style=flat-square&label=repos&color=blue)](https://github.com/pz-forge?tab=repositories)
[![Since](https://img.shields.io/badge/on%20GitHub-since%202018-181717?style=flat-square&logo=github)](https://github.com/pz-forge)

</div>

---

## 在做什么

共同点是：**现有工具不好用，就自己动手**。

**AI 接入层** — 把散在各处的模型能力接到手边。多账号网关、协议转换、客户端适配，目标是让 Codex / Claude Code / OpenAI 兼容客户端都能无缝用上。

**安全与逆向** — 从行为层面看清一个程序在干什么。窗口级逆向、运行时干预、暴露面测绘。不满足于"它弹广告"，要弄清楚是哪一行、哪个窗口、哪次 HTTP 请求。

**工具与创作** — 写给自己用的效率工具，以及把 AI 接到实际产出上的尝试。能自动化的重复劳动就不手动点。

## 仓库

### AI 工具链

| 项目 | 说明 |
|---|---|
| **[workbuddy2api-hub](https://github.com/pz-forge/workbuddy2api-hub)** | WorkBuddy 国际/国内多账号反代网关，支持 Codex、Claude Code、DSH 与标准 OpenAI 客户端 |

### 安全与逆向

| 项目 | 说明 |
|---|---|
| **[RaiDrive-AdGuard](https://github.com/pz-forge/RaiDrive-AdGuard)** | 干掉 RaiDrive Mount 的开机广告弹窗。WinEvent 钩子按住 WebView2 广告外壳，画出之前就关掉。不碰原程序，不破签名 |

### 工具与创作

| 项目 | 说明 |
|---|---|
| **[LumaRescue](https://github.com/pz-forge/LumaRescue)** | 面向 Codex / 豆包桌面版的 AI 废片拯救技能，光影重塑、构图重构、修复与审美增强 |

## 手边的东西

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

</div>

## 做事的习惯

- **先搞清楚原因，再动手。** 绕过问题的补丁不算修好，知道它在哪一行出的错才算
- **能用就不用，不用就不加。** 不为不可能发生的情况堆防御代码
- **验证过才叫完成。** 没跑通、没测过的，不说"应该可以"

---

<div align="center">

有问题开 issue，或者直接看代码。写得都挺直白。

</div>
