---
hide:
  - toc
---

<div style="text-align: center;">
  <div class="centered-logo-text-group">
    <img src="assets/agent-development-kit.png" alt="Agent Development Kit Logo" width="100">
    <h1>Agent Development Kit</h1>
  </div>
</div>

## What is Agent Development Kit?

Agent Development Kit (ADK) is a flexible and modular framework for **developing
and deploying AI agents**. While optimized for Gemini and the Google ecosystem,
ADK is **model-agnostic**, **deployment-agnostic**, and is built for
**compatibility with other frameworks**. ADK was designed to make agent
development feel more like software development, to make it easier for
developers to create, deploy, and orchestrate agentic architectures that range
from simple tasks to complex workflows.

<div class="install-command-container">
  <p style="text-align:center;">
    Get started:
    <br/>
    <code>pip install google-adk</code>
  </p>
</div>

<p style="text-align:center;">
  <a href="get-started/quickstart/" class="md-button" style="margin:3px">Quickstart</a>
  <a href="tutorials/" class="md-button" style="margin:3px">Tutorials</a>
  <a href="http://github.com/google/adk-samples" class="md-button" target="_blank" style="margin:3px">Sample Agents</a>
  <a href="api-reference/" class="md-button" style="margin:3px">API Reference</a>
  <a href="contributing-guide/" class="md-button" style="margin:3px">Contribute ❤️</a>
</p>

---

## Learn more

<div class="grid cards" markdown>

-   :material-transit-connection-variant: **Flexible Orchestration**

    ---

    Define workflows using workflow agents (`Sequential`, `Parallel`, `Loop`)
    for predictable pipelines, or leverage LLM-driven dynamic routing
    (`LlmAgent` transfer) for adaptive behavior.

    [**Learn about agents**](agents/index.md)

-   :material-graph: **Multi-Agent Architecture**

    ---

    Build modular and scalable applications by composing multiple specialized
    agents in a hierarchy. Enable complex coordination and delegation.

    [**Explore multi-agent systems**](agents/multi-agents.md)

-   :material-toolbox-outline: **Rich Tool Ecosystem**

    ---

    Equip agents with diverse capabilities: use pre-built tools (Search, Code
    Exec), create custom functions, integrate 3rd-party libraries (LangChain,
    CrewAI), or even use other agents as tools.

    [**Browse tools**](tools/index.md)

-   :material-rocket-launch-outline: **Deployment Ready**

    ---

    Containerize and deploy your agents anywhere – run locally, scale with
    Vertex AI Agent Engine, or integrate into custom infrastructure using Cloud
    Run or Docker.

    [**Deploy agents**](deploy/index.md)

-   :material-clipboard-check-outline: **Built-in Evaluation**

    ---

    Systematically assess agent performance by evaluating both the final
    response quality and the step-by-step execution trajectory against
    predefined test cases.

    [**Evaluate agents**](evaluate/index.md)

-   :material-console-line: **Building Safe and Secure Agents**

    ---

    Learn how to building powerful and trustworthy agents by implementing
    security and safety patterns and best practices into your agent's design.

    [**Safety and Security**](safety/index.md)

</div>

!!! Preview

    This feature is subject to the "Pre-GA Offerings Terms" in the General
    Service Terms section of the
    [Service Specific Terms](https://cloud.google.com/terms/service-terms#1).
    Pre-GA features are available "as is" and might have limited support. For
    more information, see the
    [launch stage descriptions](https://cloud.google.com/products#product-launch-stages).

<div class="footer"></div>
