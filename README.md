<div align="center">

<img src="./assets/portfolio-banner.svg" alt="Wenxuan Zhang — AI Agent and AI Application Engineering" width="100%" />

### AI Agent 开发 / 大模型应用开发

华东师范大学软件工程 · 2027 届 · 上海

[ChatECNU](https://chat.ecnu.edu.cn/) · [Email](mailto:wxzhang0122@gmail.com) · [Open-source Work](https://github.com/Vinsenz0122?tab=repositories)

</div>

> 我关注的不只是让模型“能回答”，而是把 **Agent 编排、工具与知识、长任务运行时、业务一致性** 组合成可以上线、恢复和评测的 AI 应用。

## 能力地图

| 能力方向 | 我解决的问题 | 项目中的实现 |
| --- | --- | --- |
| **Multi-Agent 编排** | 多个 Agent 如何拆解任务、共享事实并在部分失败后继续推进 | 以共享 Blackboard 承载结构化任务状态，通过 Schema 契约、DAG 依赖与批量委派协调子 Agent；对长对话采用窗口保留、语义摘要与关键状态固化的分层压缩策略 |
| **MCP / RAG / 工具治理** | 如何让 Agent 找到正确工具和知识，同时控制权限与副作用 | 动态筛选 MCP 工具、敏感操作人工确认与单次授权；建设多模态 Notebook，完成异步索引、Dense Retrieval、Rerank、作用域隔离与可追溯引用 |
| **长任务可靠运行** | 模型进程崩溃、连接中断或写操作结果不明时，任务如何恢复 | 将会话、运行、研究节点、Checkpoint 与 Artifact 持久化；以执行声明、连接代次、结果对账和副作用不重放处理不确定状态，并通过故障注入验证恢复路径 |
| **AI 应用工程化** | 多模型接入和真实业务中的额度、幂等、限流与可观测性 | 统一 Provider Registry / Adapter；实现调用幂等、额度预留—结算—释放、账本对账、消息队列、Redis 限流、SSE 与 Trace |

## 代表项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://chat.ecnu.edu.cn/">ChatECNU</a></h3>
      <p><strong>华东师范大学官方智能助手 · 已上线</strong></p>
      <p>负责 Agent 工具链、多模态 Notebook 与校园业务接入。将 16 个可选 MCP 按任务动态筛选为单轮 0–3 个候选工具，并为敏感写操作加入人工确认、单次授权和断点恢复；Notebook 支持文件、网页、图片、音频入库，以及检索重排、权限隔离和引用回写。</p>
      <p><code>LangGraph</code> <code>MCP</code> <code>RAG</code> <code>Qdrant</code> <code>Redis</code> <code>SSE</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/waooAI/waoowaoo">Waoowaoo</a></h3>
      <p><strong>13K+ Stars 开源 AI 影视项目 · 参与开发</strong></p>
      <p>围绕多 Agent 协作重构创作流程：主 Agent 拆解并批量委派，子 Agent 通过结构化任务契约和共享状态协作，依赖图控制执行顺序，聚合层处理乱序完成、局部失败与结果回传；同时设计长上下文分层压缩，保留角色、分镜和创作约束。</p>
      <p><a href="https://github.com/Vinsenz0122/waoowaoo">我的工作分支</a> · <code>Multi-Agent</code> <code>Blackboard</code> <code>DAG</code> <code>Context</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Re-Searching</h3>
      <p><strong>长期科研 Agent 与可靠运行时 · 实习项目 / 内部</strong></p>
      <p>面向长历史恢复，将 Codex 对话切片、子 Agent 引用、Evidence 与 State Delta 重建为可追踪 Research Graph；在运行时以持久化执行声明、连接代次和结果对账处理崩溃与未知结果，避免副作用请求被自动重放。</p>
      <p><code>Agent Runtime</code> <code>History Recovery</code> <code>Checkpoint</code> <code>Evaluation</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>AAC</h3>
      <p><strong>统一模型能力与应用基础设施 · 实习项目 / 内部</strong></p>
      <p>通过 Registry 与 Adapter 统一文本、视觉和生成类模型调用，当前代码配置覆盖 51 个模型、35 个已启用公开 ModelScope 模型与 9 类任务；围绕论坛互动和代币消费实现幂等、额度预留—结算—释放、账本审计及异常对账。</p>
      <p><code>Provider Adapter</code> <code>Model Gateway</code> <code>Idempotency</code> <code>Ledger</code></p>
    </td>
  </tr>
</table>

## 可公开验证的作品

| Repository | 展示的工程能力 |
| --- | --- |
| [ai-capability-service-zhangwenxuan](https://github.com/Vinsenz0122/ai-capability-service-zhangwenxuan) | FastAPI 模型能力网关：Provider 抽象、统一错误协议、request_id、耗时日志、密钥隔离、Pytest 与 CI |
| [openclaw-chat-agent-workbench](https://github.com/Vinsenz0122/openclaw-chat-agent-workbench) | 本地优先的 Agent 工作台：LangGraph 工具循环、SSE、Memory / RAG、安全中间件和 Langfuse Trace |
| [codex-web-test-skill](https://github.com/Vinsenz0122/codex-web-test-skill) | 面向 Codex 的 Web 测试工作流：需求建模、浏览器证据、Playwright 检查与可复核报告 |
| [medical-ai-assistant-platform](https://github.com/Vinsenz0122/medical-ai-assistant-platform) | Vue + Spring Boot + FastAPI 的异步 AI 业务流程、角色工作台与结果审核界面 |

## 技术与工程习惯

- **Agent / AI：**LangGraph、Multi-Agent、MCP、Tool Calling、RAG、Memory、Agent Eval
- **Backend：**Python / FastAPI、Java / Spring Boot、Redis、消息队列、关系型数据库、Docker
- **Frontend：**TypeScript、React / Next.js、Vue；能够独立完成流式交互、任务工作台和管理端
- **Delivery：**熟练使用 Codex、Claude Code；重视结构化日志、Trace、自动化测试、故障恢复与可验证交付

## 当前方向

寻找 **上海 · 2027 校招** 的 AI Agent 开发、大模型应用开发或 AI 全栈岗位。欢迎通过 [wxzhang0122@gmail.com](mailto:wxzhang0122@gmail.com) 联系我。

<sub>说明：公开项目均提供仓库或线上入口；内部项目只展示可公开讨论的架构与已核验数据，评测方案不作为尚未实测的结果呈现。</sub>
