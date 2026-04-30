<div align="center">

<img src="./assets/portfolio-banner.svg" alt="visenz0122 - AI Agent application engineering profile" width="100%" />

<br />

<a href="https://github.com/visenz0122">GitHub</a> ·
<a href="mailto:wxzhang0122@gmail.com">wxzhang0122@gmail.com</a> ·
Shanghai · Frontend-first AI full-stack engineering

</div>

## Profile

I am building toward an **AI application engineering** role with a frontend-first full-stack base. My strongest work is turning model or Agent behavior into product surfaces people can actually use: streaming responses, tool-call visibility, memory retrieval, async AI task state, safety boundaries, and reviewable workflows.

I do not use low-value activity widgets here. This page is meant to show what I can explain, demo, debug, and keep improving.

## Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/visenz0122/openclaw-chat-agent-workbench">OpenClaw Chat Agent Workbench</a>
      </h3>
      <p>
        <strong>Personal AI Agent workbench.</strong> I built this as a local-first system for streaming chat, tool orchestration, structured memory, safety checks, and traceable Agent runtime behavior.
      </p>
      <p><strong>What it demonstrates</strong></p>
      <ul>
        <li>Next.js workspace for chat, sessions, runtime config, file editing, and event inspection.</li>
        <li>FastAPI SSE path from user message to LangChain/LangGraph Agent execution.</li>
        <li>Memory v1/v2 with JSON sessions, Chroma/vector search, PostgreSQL + pgvector, BM25, and hybrid retrieval.</li>
        <li>Guardian middleware and optional Langfuse tracing for safer, observable Agent behavior.</li>
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

## Engineering Focus

| Focus | What I am trying to prove |
| --- | --- |
| AI product frontend | I can design dense workspaces for chat, long-running tasks, editor panels, role workflows, and streaming event feedback. |
| Agent integration | I can connect UI state to SSE contracts, tool-call events, memory injection, safety middleware, and LangGraph runtime behavior. |
| Full-stack coordination | I can work across REST/SSE APIs, FastAPI services, Spring Boot business logic, PostgreSQL state, and local Docker startup paths. |
| Delivery discipline | I care about failure states, traceability, acceptance demos, readable docs, and wording that does not overclaim. |

## System Map

```text
OpenClaw
  user message -> SSE stream -> Agent runtime -> tools / memory / safety -> inspectable UI

Medical AI platform
  image case -> async inference task -> result state -> feedback / research / audit -> Agent HITL
```

## Stack I Can Discuss

<p>
  <code>TypeScript</code>
  <code>React</code>
  <code>Next.js</code>
  <code>Vue 3</code>
  <code>Tailwind CSS</code>
  <code>Element Plus</code>
  <code>FastAPI</code>
  <code>Spring Boot</code>
  <code>PostgreSQL</code>
  <code>pgvector</code>
  <code>LangGraph</code>
  <code>LangChain</code>
  <code>SSE</code>
  <code>RAG</code>
  <code>Docker</code>
  <code>Playwright</code>
</p>

## Open Source Systems I Study

| System | Why it matters to my direction |
| --- | --- |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Stateful Agent workflows and controllable execution graphs. |
| [Dify](https://github.com/langgenius/dify) | Production-style LLM workflow and application platform design. |
| [OpenHands](https://github.com/OpenHands/OpenHands) | Developer-agent UX and software engineering Agent patterns. |
| [browser-use](https://github.com/browser-use/browser-use) | Browser automation as an Agent capability. |
| [Vercel AI SDK](https://github.com/vercel/ai) | TypeScript-first streaming AI application patterns. |
| [Langfuse](https://github.com/langfuse/langfuse) | LLM tracing, prompt observability, and evaluation workflows. |
