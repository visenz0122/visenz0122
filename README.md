<div align="center">

<img src="./assets/portfolio-banner.svg" alt="visenz0122 - AI application engineering and Codex tooling profile" width="100%" />

<br />

<a href="https://github.com/visenz0122">GitHub</a> ·
<a href="mailto:wxzhang0122@gmail.com">wxzhang0122@gmail.com</a> ·
Shanghai · AI application engineering · Codex tooling

</div>

## Portfolio Map

I focus on **AI application engineering** with a frontend-first full-stack base. The projects below are organized by what they prove, not by raw activity numbers.

| Lane | Public artifact | Engineering signal |
| --- | --- | --- |
| Agent workbench | [OpenClaw Chat Agent Workbench](https://github.com/visenz0122/openclaw-chat-agent-workbench) | Streaming Agent UI, tool-call visibility, memory retrieval, safety middleware, traceable runtime behavior. |
| Applied AI workflow | [Medical AI Assistant Platform](https://github.com/visenz0122/medical-ai-assistant-platform) | Role-based Vue workflows, async inference state, Spring Boot/FastAPI integration, PostgreSQL-backed records. |
| Developer tooling | [spec-test.skill](https://github.com/visenz0122/spec-test.skill) | Skill design, specification-based testing, browser/Playwright evidence, reusable QA workflow templates. |

## Main Case Studies

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/visenz0122/openclaw-chat-agent-workbench">OpenClaw Chat Agent Workbench</a>
      </h3>
      <p>
        <strong>Personal AI Agent workbench.</strong> I built this as a local-first system for streaming chat, tool orchestration, structured memory, safety checks, and observable Agent execution.
      </p>
      <p><strong>What it demonstrates</strong></p>
      <ul>
        <li>Next.js workspace for chat, session switching, runtime config, file editing, and event inspection.</li>
        <li>FastAPI SSE path from user message to LangChain/LangGraph Agent execution.</li>
        <li>Memory v1/v2 with JSON sessions, Chroma/vector search, PostgreSQL + pgvector, BM25, and hybrid retrieval.</li>
        <li>Guardian middleware and optional Langfuse tracing for safer, inspectable Agent behavior.</li>
      </ul>
      <p>
        <code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>FastAPI</code>
        <code>LangGraph</code> <code>LangChain</code> <code>PostgreSQL</code> <code>pgvector</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/visenz0122/medical-ai-assistant-platform">Medical AI Assistant Platform</a>
      </h3>
      <p>
        <strong>Course/team full-stack AI workflow project.</strong> The public positioning is intentionally honest: my strongest angle is frontend-heavy integration and AI application delivery.
      </p>
      <p><strong>What it demonstrates</strong></p>
      <ul>
        <li>Vue 3 role workflows for doctors, researchers, admins, and Agent-assisted operations.</li>
        <li>Async pneumonia inference task states, result review, feedback, and failure recovery UI.</li>
        <li>Integration across Spring Boot business APIs, FastAPI CV inference, FastAPI Agent service, and PostgreSQL.</li>
        <li>Acceptance docs, demo routes, testing notes, and release-readiness material organization.</li>
      </ul>
      <p>
        <code>Vue 3</code> <code>TypeScript</code> <code>Spring Boot</code> <code>FastAPI</code>
        <code>PostgreSQL</code> <code>LangGraph</code> <code>Docker</code> <code>Playwright</code>
      </p>
    </td>
  </tr>
</table>

## Developer Tooling

### [spec-test.skill](https://github.com/visenz0122/spec-test.skill)

`spec-test.skill` is my public skill project for agent-assisted web testing. It turns vague "test this feature" requests into structured specifications, test cases, execution evidence, and reviewable QA reports.

| Area | What it contains |
| --- | --- |
| Spec workflow | Cartographer, Inspector, and Operator roles with human review gates. |
| Test design | Boundary value, equivalence partitioning, decision table, state transition, use case, and Right-BICEP references. |
| Execution discipline | Playwright plus browser/screenshot evidence for data, workflow, and visual checks. |
| Reusable artifacts | Chinese and English editions, templates, examples, execution reports, and review checklists. |

## Engineering Signals

| Signal | Evidence across the projects |
| --- | --- |
| Product-grade AI frontend | Streaming chat surfaces, long-running task states, role workflows, editor panels, result review, and event feedback. |
| Agent integration | SSE contracts, tool-call rendering, memory/RAG injection, LangGraph runtime control, Guardian checks, and tracing. |
| Full-stack coordination | REST/SSE APIs, FastAPI services, Spring Boot business logic, PostgreSQL records, Docker/local startup paths. |
| Testing and delivery | Specification-based testing, browser evidence, Playwright thinking, acceptance docs, and honest public wording. |

## Stack

| Layer | Tools I can discuss from real project work |
| --- | --- |
| Frontend surfaces | TypeScript, React, Next.js, Vue 3, Tailwind CSS, Element Plus, Monaco-style editor/workspace patterns. |
| Agent / AI application | LangGraph, LangChain, SSE streaming, tool calls, memory retrieval, RAG, safety middleware, Langfuse-style tracing. |
| Backend / data | FastAPI, Spring Boot, PostgreSQL, pgvector, Chroma, Docker Compose, auth/RBAC integration. |
| QA / developer tools | Skill authoring, specification-based testing, browser automation, Playwright, screenshot evidence, test report templates. |

<details>
<summary>Open source systems I study</summary>

| System | Why it matters to my direction |
| --- | --- |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Stateful Agent workflows and controllable execution graphs. |
| [Dify](https://github.com/langgenius/dify) | Production-style LLM workflow and application platform design. |
| [OpenHands](https://github.com/OpenHands/OpenHands) | Developer-agent UX and software engineering Agent patterns. |
| [browser-use](https://github.com/browser-use/browser-use) | Browser automation as an Agent capability. |
| [Vercel AI SDK](https://github.com/vercel/ai) | TypeScript-first streaming AI application patterns. |
| [Langfuse](https://github.com/langfuse/langfuse) | LLM tracing, prompt observability, and evaluation workflows. |

</details>
