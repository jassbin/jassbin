<h1 align="center">jazz · jassbin</h1>

<p align="center">
  <b>把模糊的想法压成一套方法论，再让 AI 按方法论产出能跑的东西。</b><br/>
  <sub>不是造轮子 —— 是把「说不清的感觉」变成「可验证的结构」。</sub>
</p>

---

## 三个能马上点开的

### 🖐️ [手势魔方 Gesture Cube](https://github.com/jassbin/gesture-cube) · [手机试玩 ↗](https://gesture-cube-d5c0aace.eazo.dev)

打开手机后置摄像头，**用手在空中拧一个 3D 魔方**。
没有深度传感器 —— 只有 MediaPipe 给出的 21 个 **2D** 关键点，靠交互设计把抖动变成可控操作。

> 用手形传达意图 · 用停顿确认 · 用锁定换稳定 · 用 1:1 换直觉 · 用防误触换信任

`three.js` · `MediaPipe` · `Next.js` · `MIT`

<br/>

### 📖 [难得读书 mybook](https://github.com/jassbin/mybook) · [在线体验 ↗](https://mybook-3eb25c73.eazo.dev)

**变成名著里的角色**，替他做 3 次两难抉择，然后照见你自己。
17 条设计原则分三层（宪法级红线 / 体验支柱 / 实施手艺），每条带 `tier` 按 L1→L3 排序注入每幕 prompt —— 冲突时低层永远为高层让步。

`Next.js 16` · `LLM Agent` · `MCP Server` · `CC BY-NC 4.0`

<br/>

### 🔧 [Codex 429 排队网关](https://github.com/jassbin/codex-429-queue-gateway)

**429 不是网络问题** —— 它是「请求已经到达服务器，被并发上限拒绝」。
用约 200 行本地网关根治第三方 OpenAI 兼容网关的超限，附 4 个月日志取证、压测矩阵与踩坑清单。

`aiohttp` · `SSE 透传` · `MIT`

---

## 我反复在用的几招

| 招 | 一句话 | 在哪能看到 |
|---|---|---|
| **原则分层 + tier 注入** | 把产品纪律写进 prompt：L1 宪法级红线 / L2 体验支柱 / L3 实施手艺，冲突时低层让步 | [mybook](https://github.com/jassbin/mybook) |
| **反向产品化** | 先做 → 从产物里提炼原则 → 拿原则当尺子反推缺口 → 补强 → 再提炼 | [mybook/docs](https://github.com/jassbin/mybook/tree/main/docs) |
| **证据驱动调试** | 抓响应体 → 按变量二分 → 再压并发。先定性再动手，不靠猜 | [codex-429](https://github.com/jassbin/codex-429-queue-gateway) |
| **把噪声变成确定性** | 用「停顿」当确认、用「锁定」当状态、用代价不对称性定阈值 | [gesture-cube](https://github.com/jassbin/gesture-cube) |
| **信源分级 T1–T5** | 纯规则零 LLM 给证据打权威分 + 跨源交叉印证 | [deep-analysis-workbench](https://github.com/jassbin/deep-analysis-workbench) |

---

## 其他在做的事

- **[照妖镜 Structure Lens](https://github.com/jassbin/structure-lens)** — 一键拆解热点事件的 8 步结构穿透，找出谁在提取价值、谁在承担代价 · [在线 ↗](https://structure-lens-8c3bf836.eazo.dev)
- **[清醒行动主义](https://github.com/jassbin/qingxing-actionism)** — 一套生存哲学 AI Skill：痛是信号不是命运，行动优先于反思，永远不美化自欺（四版谱系完整归档）
- **[西游人格测试](https://github.com/jassbin/xiyou-personality-test)** — 《牛来》画风五维价值观测试，小程序 + 浏览器双端 · [玩一下 ↗](https://xyj.jasss.art)
- **[跨境套利指挥台](https://github.com/jassbin/arbitrage-cockpit)** — 国外需求 → 到手净利 → 国内产能匹配 → 防跳单审计 → 回款账本
- **[出海指挥官](https://github.com/jassbin/export-commander-ai)** — 跨境外贸 AI 营销总控台：策略 → 素材 → 种草投流 → 诊断 → 迭代

---

<p align="center">
  <sub>大多数仓库都带了完整的「问题 → 取证 → 解法 → 踩坑」复盘，欢迎直接翻 README。</sub>
</p>
