<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0f172a,55:0e7490,100:f59e0b&text=P0lar1ght&fontColor=ffffff&fontSize=48&fontAlignY=36&desc=Vulnerability%20Research%20%7C%20AI%20Security%20%7C%20Java%20Security%20%7C%20Red%20Team%20Tooling&descAlignY=58&descSize=16" alt="P0lar1ght" />
</p>

<p align="center">
  <a href="https://p0lar1ght.github.io"><img src="https://img.shields.io/badge/Blog-p0lar1ght.github.io-0e7490?style=for-the-badge&logo=githubpages&logoColor=white" alt="Blog" /></a>
  <a href="https://github.com/P0lar1ght?tab=repositories"><img src="https://img.shields.io/badge/Focus-Red%20Team%20Tooling-f59e0b?style=for-the-badge&logo=gnometerminal&logoColor=white" alt="Red Team Tooling" /></a>
  <a href="https://github.com/P0lar1ght?tab=stars"><img src="https://img.shields.io/badge/Research-Vulnerability%20Discovery-111827?style=for-the-badge&logo=target&logoColor=white" alt="Vulnerability Research" /></a>
  <a href="https://github.com/P0lar1ght?tab=repositories"><img src="https://img.shields.io/badge/Security-AI%20%26%20Java-0e7490?style=for-the-badge&logo=openjdk&logoColor=white" alt="AI and Java Security" /></a>
</p>
<p align="center"><sub>AI 安全 · 红队工具 · Java/JVM 攻防 · CPG 代码分析 · CyberGym </sub></p>

## 统计 / Stats

<p align="center">
  <img src="https://img.shields.io/github/stars/P0lar1ght?label=Stars&style=flat-square" alt="Stars" />
  <img src="https://img.shields.io/github/followers/P0lar1ght?label=Followers&style=flat-square" alt="Followers" />
  <a href="https://github.com/P0lar1ght?tab=repositories"><img src="https://img.shields.io/badge/Repos-public-0e7490?style=flat-square" alt="Repos" /></a>
</p>


<p align="center">
  <a href="https://github.com/P0lar1ght/JVMHeapAnalyzer"><img src="https://img.shields.io/github/stars/P0lar1ght/JVMHeapAnalyzer?style=flat-square&label=JVMHeapAnalyzer" alt="JVMHeapAnalyzer" /></a>
  <a href="https://github.com/P0lar1ght/SunGods"><img src="https://img.shields.io/github/stars/P0lar1ght/SunGods?style=flat-square&label=SunGods" alt="SunGods" /></a>
  <a href="https://github.com/P0lar1ght/argus"><img src="https://img.shields.io/github/stars/P0lar1ght/argus?style=flat-square&label=Argus" alt="Argus" /></a>
  <a href="https://github.com/P0lar1ght/PolarBytes"><img src="https://img.shields.io/github/stars/P0lar1ght/PolarBytes?style=flat-square&label=PolarBytes" alt="PolarBytes" /></a>
</p>


<p>
  <img height="160" src="https://github-readme-stats-one-bice.vercel.app/api?username=P0lar1ght&show_icons=true&theme=transparent&hide_border=true&rank_icon=github&include_all_commits=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=P0lar1ght&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />
</p>

## 目录 / Contents

- [关于我 / About](#关于我--about)
- [项目 / Projects](#项目--projects)
- [研究方向 / Research](#研究方向--research)
- [~~技术栈 / Tech Stack~~](#技术栈--tech-stack)

## 关于我 / About

做漏洞挖掘和红队相关工作，最近一半时间在搞 **AI + 安全**，一半在 **Java / 红队工具**。

会写平台和 CLI，也会抠 JVM 堆、内存痕迹、内存马这类偏底层的东西。有用的会尽量开源；笔记和实验多在仓库与本地整理，[主页](https://p0lar1ght.github.io) 更新不多，当个导航用就行。

I work on vulnerability research and red teaming — lately about half **AI + security**, half **Java / red team tooling**.

I build platforms and CLIs, and dig into lower-level stuff like JVM heaps, in-memory artifacts, and memory webshells. Useful work gets open-sourced when I can; notes live mostly in repos and local archives. The [homepage](https://p0lar1ght.github.io) is sparse — more of a hub than a blog.

## 项目 / Projects

### AI / Agent

| 项目 / Project | 说明 / Description |
|------|------|
| [PolarVigil](https://github.com/P0lar1ght/PolarVigil) | 本地 Agent Runtime（Runtime / Gateway / CLI / SDK），给别的产品嵌 Agent 用，不绑死某一家业务。二进制发布在 [PolarVigil-Releases](https://github.com/P0lar1ght/PolarVigil-Releases) |
| [WeepCode](https://github.com/Captain-AI-Hub/WeepCode) | 终端 AI 编码助手（TUI），自带多 Provider，能改代码、跑命令、做长任务 |
| [Argus](https://github.com/P0lar1ght/argus) | 分布式攻击面管理 / 漏洞巡航，带 AI Copilot 辅助运营（ASM + 任务编排 + 弹药库） |

### 红队 / Red Team Tools

| 项目 / Project | 说明 / Description |
|------|------|
| [SunGods](https://github.com/P0lar1ght/SunGods) | 授权场景下的综合渗透平台（会话、Payload、插件、MCP、和 PolarBytes 能力对接） |
| [PolarBytes](https://github.com/P0lar1ght/PolarBytes) | 内存马 / 字节码 / Wrapper / Agent JAR 生成能力，SDK 给宿主项目用 |
| [JVMHeapAnalyzer](https://github.com/P0lar1ght/JVMHeapAnalyzer) | Java 堆 dump 分析，挖环境信息、框架密钥、凭据等运行时痕迹 |
| [SunLoginHacker](https://github.com/P0lar1ght/SunLoginHacker) | 远控客户端内存痕迹研究（授权环境） |
| [ToDeskHacker](https://github.com/P0lar1ght/ToDeskHacker) | 远控客户端内存痕迹研究（授权环境） |

## 研究方向 / Research

- **AI + 安全 / AI + Security**：LLM Agent 在攻击面管理、代码审计、漏洞研判中的落地；MCP / Tool-use 协议在安全工具链里的集成
- **Java / JVM 攻防 / Java & JVM Offense-Defense**：反序列化与利用链、内存马形态与检测点、堆 dump / 内存痕迹里的敏感信息
- **RASP 研究 / RASP Research**：商业/开源 Agent 的加载链路、Hook 切点、规则面与绕过边界（以可复现分析笔记为主）
- **CPG + Joern**：建图、污点与调用链追踪，接到 MCP / Agent，支撑代码审计和 cyber 研判
- **产品与组件漏洞 / Product & Component Vulns**：业务系统、中间件相关漏洞的发现、复现与影响面评估

研究默认只在 **授权或自建靶场** 里做利用验证；结论尽量可复现，利用细节服务修复与检测，不面向未授权滥用。

Research is limited to **authorized or self-hosted labs**. Findings aim to be reproducible; exploit detail supports defense and detection — not unauthorized abuse.

## ~~技术栈 / Tech Stack~~

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Codex-412991?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTIyLjI4MiA5LjgyMWE1Ljk4NSA1Ljk4NSAwIDAgMC0uNTE2LTQuOTEgNi4wNDYgNi4wNDYgMCAwIDAtNi41MS0yLjlBNi4wNjUgNi4wNjUgMCAwIDAgNC45ODEgNC4xOGE1Ljk4NSA1Ljk4NSAwIDAgMC0zLjk5OCAyLjkgNi4wNDYgNi4wNDYgMCAwIDAgLjc0MyA3LjA5NyA1Ljk4IDUuOTggMCAwIDAgLjUxIDQuOTExIDYuMDUxIDYuMDUxIDAgMCAwIDYuNTE1IDIuOUE1Ljk4NSA1Ljk4NSAwIDAgMCAxMy4yNiAyNGE2LjA1NiA2LjA1NiAwIDAgMCA1Ljc3Mi00LjIwNiA1Ljk5IDUuOTkgMCAwIDAgMy45OTctMi45IDYuMDU2IDYuMDU2IDAgMCAwLS43NDctNy4wNzN6TTEzLjI2IDIyLjQzYTQuNDc2IDQuNDc2IDAgMCAxLTIuODc2LTEuMDRsLjE0MS0uMDgxIDQuNzc5LTIuNzU4YS43OTUuNzk1IDAgMCAwIC4zOTItLjY4MXYtNi43MzdsMi4wMiAxLjE2OGEuMDcxLjA3MSAwIDAgMSAuMDM4LjA1MnY1LjU4M2E0LjUwNCA0LjUwNCAwIDAgMS00LjQ5NCA0LjQ5NHpNMy42IDE4LjMwNGE0LjQ3IDQuNDcgMCAwIDEtLjUzNS0zLjAxbC4xNDIuMDg1IDQuNzgzIDIuNzU5YS43NzEuNzcxIDAgMCAwIC43OCAwbDUuODQzLTMuMzY5djIuMzMyYS4wOC4wOCAwIDAgMS0uMDMzLjA2Mkw5Ljc0IDE5Ljk1YTQuNSA0LjUgMCAwIDEtNi4xNC0xLjY0NnpNMi4zNCA3Ljg5NmE0LjQ4NSA0LjQ4NSAwIDAgMSAyLjM2Ni0xLjk3M1YxMS42YS43NjYuNzY2IDAgMCAwIC4zODguNjc2bDUuODE1IDMuMzU1LTIuMDIgMS4xNjhhLjA3Ni4wNzYgMCAwIDEtLjA3MSAwbC00LjgzLTIuNzg2QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQgNy44NzJ6bTE2LjU5NyAzLjg1NWwtNS44MzMtMy4zODdMMTUuMTE5IDcuMmEuMDc2LjA3NiAwIDAgMSAuMDcxIDBsNC44MyAyLjc5MWE0LjQ5NCA0LjQ5NCAwIDAgMS0uNjc2IDguMTA1di01LjY3OGEuNzkuNzkgMCAwIDAtLjQwNy0uNjY3em0yLjAxLTMuMDIzbC0uMTQxLS4wODUtNC43NzQtMi43ODJhLjc3Ni43NzYgMCAwIDAtLjc4NSAwTDkuNDA5IDkuMjNWNi44OTdhLjA2Ni4wNjYgMCAwIDEgLjAyOC0uMDYxbDQuODMtMi43ODdhNC41IDQuNSAwIDAgMSA2LjY4IDQuNjZ6bS0xMi42NCA0LjEzNWwtMi4wMi0xLjE2NGEuMDguMDggMCAwIDEtLjAzOC0uMDU3VjYuMDc1YTQuNSA0LjUgMCAwIDEgNy4zNzUtMy40NTNsLS4xNDIuMDhMOC43MDQgNS40NmEuNzk1Ljc5NSAwIDAgMC0uMzkzLjY4MXptMS4wOTctMi4zNjVsMi42MDItMS41IDIuNjA3IDEuNXYyLjk5OWwtMi41OTcgMS41LTIuNjA3LTEuNXoiLz48L3N2Zz4=&logoColor=white" alt="Codex" />
  <img src="https://img.shields.io/badge/Grok-1a1a1a?style=flat-square&logo=x&logoColor=white" alt="Grok" />
  <img src="https://img.shields.io/badge/Claude%20Code-6e47d4?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square&logo=deepseek&logoColor=white" alt="DeepSeek" />
  <img src="https://img.shields.io/badge/Zcode-2D2D2D?style=flat-square&logo=zdotai&logoColor=white" alt="Zcode" />
  <img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=flat-square&logo=stackoverflow&logoColor=white" alt="Stack Overflow" />
</p>


## 贡献轨迹 / Contribution Snake

<p align="center">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/P0lar1ght/P0lar1ght/output/github-contribution-grid-snake.svg" />
</p>

<p align="center">
  <img alt="github contribution grid snake animation dark" src="https://raw.githubusercontent.com/P0lar1ght/P0lar1ght/output/github-contribution-grid-snake-dark.svg" />
</p>

内容默认面向 **授权测试与安全研究**。主页：[p0lar1ght.github.io](https://p0lar1ght.github.io)。

Content is intended for **authorized testing and security research** only. Homepage: [p0lar1ght.github.io](https://p0lar1ght.github.io).

<!-- BLOG-START -->
<!-- BLOG-END -->
