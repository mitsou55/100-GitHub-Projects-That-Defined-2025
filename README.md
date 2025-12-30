## FAUN·dev() - Empowering Developers
FAUN·dev() is a developer-first platform built around a simple idea: pay attention to what engineers actually care about. It aggregates, curates, and distributes tools, articles, and resources across the modern software stack.

The ecosystem is organized around a broader platform where [developers can publish posts](https://faun.dev), curate and share tools, [keep up with latest tech news and innovations](https://faun.dev/news), create dedicated pages to showcase their own projects, learn through structured educational content via [FAUN·sensei()](https://faun.dev/sensei), and stay up to date through focused weekly newsletters covering DevOps, Kubernetes, AI/ML, programming and more!

[DevOpsLinks](https://faun.dev/newsletter/devopslinks) tracks infrastructure, cloud, and delivery tooling. [Kaptain](https://faun.dev/newsletter/kaptain) focuses on Kubernetes and the cloud-native ecosystem. [Kala](https://faun.dev/newsletter/kala) covers AI, ML, and MLOps. [VarBear](https://faun.dev/newsletter/varbear) centers on programming languages, frameworks, and core developer tools. Together, they reach a broad and technically diverse audience, from platform engineers to application developers.

Every week, thousands of readers interact with tools surfaced through these channels. Those interactions create a stream of real-world signals: what developers pause on, investigate further, and come back to.

This work presents a ranked list of the 100 developer tools developers paid the most attention to in 2025, based on aggregated platform-level interaction signals across the FAUN.dev() ecosystem (not based on surveys or editorial opinion). The ranking reflects consistent, intentional engagement from thousands of developers reading [DevOpsLinks](https://faun.dev/newsletter/devopslinks), [Kala](https://faun.dev/newsletter/kala), [VarBear](https://faun.dev/newsletter/varbear), and [Kaptain](https://faun.dev/newsletter/kaptain), spanning DevOps, Kubernetes, AI/ML, programming and more.

A small fraction of the repositories on this list are not tools in the traditional sense, but collections of resources, learning materials, or curated lists. We kept them because they also reflect important developer interests and trends.

## Interpreting the 2025 Developer Tooling Landscape

The list is long and before diving into individual entries, it's worth stepping back to identify some patterns we've observed across the top-ranked tools of 2025.

The top tools show a clear shift from "AI demos" to "AI systems." The dominant pattern is standardization around the **Model Context Protocol** and its ecosystem: curated MCP registries, frameworks for building servers and clients, official vendor implementations, and deployment helpers.

Developers are converging on a common integration surface so agents can reliably talk to real tools, real data, and real infrastructure. In parallel, coding agents are becoming workflow-native - terminal-first, repo-first, CI-friendly - with projects that emphasize orchestration, retrieval, evaluation, and practical ergonomics instead of flashy UX and gimmicks.

A second strong signal is the rise of "computer use" and ops automation: browser-driven agents and GUI agents that operate the same interfaces humans do, plus a heavy **[Kubernetes](https://faun.dev/tool/kubernetes)** thread where clusters are increasingly treated as agent-addressable control planes. Around the edges, the trends highlight growing pressure on operations fundamentals - cost visibility, privileged access, fleet management, monitoring, and incident response: as AI workloads and automation sprawl expand rapidly, teams are looking for better ways to govern. Even the more chaotic non-tool entries (like leaked prompt collections) point to a real demand: developers want guardrails, observability, and security patterns for agentic systems, not just another framework.

## Top 100 Developer Tools of 2025

### browser-use/browser-use

📊 **FAUN·dev() popularity score**: 100/100

⭐ **GitHub stars**: 74309

**Description**: Make websites accessible for AI agents

**URL**: https://github.com/browser-use/browser-use

**Latest appearance**: [Kala Issue #472 - Sec-Gemini Strikes, CUAs Rise, and Llama 4 Leads the AI Charge](https://factory.faun.dev/newsletters/i/sec-gemini-strikes-cuas-rise-and-llama-4-leads-the-ai-charge-3978a25a-2dbd-4852-b7fb-bab174160895)

---

### punkpeye/awesome-mcp-servers.

📊 **FAUN·dev() popularity score**: 80/100

⭐ **GitHub stars**: 77763

**Description**: A collection of MCP servers

**URL**: https://github.com/punkpeye/awesome-mcp-servers

**Latest appearance**: [Kala Issue #471 - Invisible AI for Interviews, Llama 4 Herd and OpenAI’s Worst Nightmare](https://factory.faun.dev/newsletters/i/invisible-ai-for-interviews-llama-4-herd-and-openais-worst-nightmare-48b8569f-db23-41af-843e-bbf510717240)

---

### manusa/kubernetes-mcp-server

📊 **FAUN·dev() popularity score**: 74/100

⭐ **GitHub stars**: 916

**Description**: Model Context Protocol (MCP) server for Kubernetes and OpenShift

**URL**: https://github.com/manusa/kubernetes-mcp-server

**Latest appearance**: [Kala Issue #472 - Sec-Gemini Strikes, CUAs Rise, and Llama 4 Leads the AI Charge](https://factory.faun.dev/newsletters/i/sec-gemini-strikes-cuas-rise-and-llama-4-leads-the-ai-charge-3978a25a-2dbd-4852-b7fb-bab174160895)

---

### jujumilk3/leaked-system-prompts

📊 **FAUN·dev() popularity score**: 69/100

⭐ **GitHub stars**: 13799

**Description**: Collection of leaked system prompts

**URL**: https://github.com/jujumilk3/leaked-system-prompts

**Latest appearance**: [Kala Issue #477 - AI at Scale: Saudi Supercomputers, GPU Giants & Serverless Agents](https://factory.faun.dev/newsletters/i/ai-at-scale-saudi-supercomputers-gpu-giants-serverless-agents-799db520-cbb4-48ce-9e56-6e9954988371)

---

### jlowin/fastmcp

📊 **FAUN·dev() popularity score**: 68/100

⭐ **GitHub stars**: 21525

**Description**: The fast, Pythonic way to build MCP servers and clients

**URL**: https://github.com/jlowin/fastmcp

**Latest appearance**: [Kala Issue #479 - Google I/O 100, OpenAI’s Smartest Model Refuses Shutdown, and the Prompt That Breaks LLMs](https://factory.faun.dev/newsletters/i/google-io-100-openais-smartest-model-refuses-shutdown-and-the-prompt-that-breaks-llms-d21e8318-d2e3-4803-be1d-f45b1cdc44cf)

---

### getzep/graphiti

📊 **FAUN·dev() popularity score**: 66/100

⭐ **GitHub stars**: 21463

**Description**: Build Real-Time Knowledge Graphs for AI Agents

**URL**: https://github.com/getzep/graphiti

**Latest appearance**: [Kala Issue #479 - Google I/O 100, OpenAI’s Smartest Model Refuses Shutdown, and the Prompt That Breaks LLMs](https://factory.faun.dev/newsletters/i/google-io-100-openais-smartest-model-refuses-shutdown-and-the-prompt-that-breaks-llms-d21e8318-d2e3-4803-be1d-f45b1cdc44cf)

---

### Jacksaur/Gorgeous-GRUB

📊 **FAUN·dev() popularity score**: 59/100

⭐ **GitHub stars**: 4375

**Description**: Collection of decent Community-made GRUB themes.

**URL**: https://github.com/Jacksaur/Gorgeous-GRUB

**Latest appearance**: [DevOpsLinks Issue #475 - AI Agents Take Over DevOps, Debian Debates Ethics, and SFTP vs FTPS Showdown](https://factory.faun.dev/newsletters/i/ai-agents-take-over-devops-debian-debates-ethics-and-sftp-vs-ftps-showdown-3662a2ca-7a23-48be-9553-01781210558a)

---

### resemble-ai/chatterbox

📊 **FAUN·dev() popularity score**: 51/100

⭐ **GitHub stars**: 18926

**Description**: SoTA open-source TTS

**URL**: https://github.com/resemble-ai/chatterbox

**Latest appearance**: [Kala Issue #481 - Disrupting Malicious AI Uses, End of Static AI & Meta's Scale AI Investment](https://factory.faun.dev/newsletters/i/disrupting-malicious-ai-uses-end-of-static-ai-metas-scale-ai-investment-4406d336-f4d3-47ef-9115-315255eab77f)

---

### microsoft/ai-agents-for-beginners

📊 **FAUN·dev() popularity score**: 48/100

⭐ **GitHub stars**: 47704

**Description**: 10 Lessons to Get Started Building AI Agents

**URL**: https://github.com/microsoft/ai-agents-for-beginners

**Latest appearance**: [Kala Issue #472 - Sec-Gemini Strikes, CUAs Rise, and Llama 4 Leads the AI Charge](https://factory.faun.dev/newsletters/i/sec-gemini-strikes-cuas-rise-and-llama-4-leads-the-ai-charge-3978a25a-2dbd-4852-b7fb-bab174160895)

---

### awslabs/mcp

📊 **FAUN·dev() popularity score**: 47/100

⭐ **GitHub stars**: 7738

**Description**: AWS MCP Servers — specialized MCP servers that bring AWS best practices directly to your development workflow

**URL**: https://github.com/awslabs/mcp

**Latest appearance**: [DevOpsLinks Issue #473 - Sec-Gemini Drops, eBPF Gets Practical, and SSL Certs Get Shorter](https://factory.faun.dev/newsletters/i/sec-gemini-drops-ebpf-gets-practical-and-ssl-certs-get-shorter-c77aed4c-1358-435c-bac9-cdf74a4aa389)

---

### browser-use/web-ui

📊 **FAUN·dev() popularity score**: 47/100

⭐ **GitHub stars**: 15359

**Description**: Run AI Agent in your browser.

**URL**: https://github.com/browser-use/web-ui

**Latest appearance**: [Kala Issue #472 - Sec-Gemini Strikes, CUAs Rise, and Llama 4 Leads the AI Charge](https://factory.faun.dev/newsletters/i/sec-gemini-strikes-cuas-rise-and-llama-4-leads-the-ai-charge-3978a25a-2dbd-4852-b7fb-bab174160895)

---

### kagent-dev/kagent

📊 **FAUN·dev() popularity score**: 46/100

⭐ **GitHub stars**: 1989

**Description**: Cloud Native Agentic AI

**URL**: https://github.com/kagent-dev/kagent

**Latest appearance**: [Kaptain Issue #470 - Every Pod Eviction Explained, Critical Ingress-nginx CVE and AI-Driven Kubernetes](https://factory.faun.dev/newsletters/i/every-pod-eviction-explained-critical-ingress-nginx-cve-and-ai-driven-kubernetes-345b9506-6479-4057-aa98-e8f1428edfd2)

---

### openai/swarm

📊 **FAUN·dev() popularity score**: 45/100

⭐ **GitHub stars**: 20744

**Description**: Educational framework exploring ergonomic, lightweight multi-agent orchestration. Managed by OpenAI Solution team.

**URL**: https://github.com/openai/swarm

**Latest appearance**: [Kala Issue #473 - Gemini’s Thinking Budget, Docker’s AI Boost & OpenAI’s Visual Sleuth](https://factory.faun.dev/newsletters/i/geminis-thinking-budget-dockers-ai-boost-openais-visual-sleuth-5bf87978-bc21-4717-ac50-8e1497cce7bb)

---

### medialab/xan

📊 **FAUN·dev() popularity score**: 45/100

⭐ **GitHub stars**: 3569

**Description**: The CSV magician

**URL**: https://github.com/medialab/xan

**Latest appearance**: [DevOpsLinks Issue #471 - The SE Identity Crisis, K8s The Hard Way and The Best AI for Coding in 2025](https://factory.faun.dev/newsletters/i/the-se-identity-crisis-k8s-the-hard-way-and-the-best-ai-for-coding-in-2025-0e4983ac-8e70-4da7-97dc-554179727fee)

---

### freelensapp/freelens

📊 **FAUN·dev() popularity score**: 43/100

⭐ **GitHub stars**: 4278

**Description**: Free IDE for Kubernetes

**URL**: https://github.com/freelensapp/freelens

**Latest appearance**: [Kaptain Issue #471 - New GUI for K8s, Recyling a Smartphone into a K8s Node and How Google Will Evolve K8s in the AI Era](https://factory.faun.dev/newsletters/i/new-gui-for-k8s-recyling-a-smartphone-into-a-k8s-node-and-how-google-will-evolve-k8s-in-the-ai-era-a8cf07d3-ca22-4787-8212-b0aae95a9844)

---

### alibaba/spring-ai-alibaba

📊 **FAUN·dev() popularity score**: 42/100

⭐ **GitHub stars**: 7661

**Description**: Agentic AI Framework for Java Developers

**URL**: https://github.com/alibaba/spring-ai-alibaba

**Latest appearance**: [DevOpsLinks Issue #477 - OpenAI’s UAE Megacenter, CI/CD Speed Boost, & Terraform Loop Magic](https://factory.faun.dev/newsletters/i/openais-uae-megacenter-cicd-speed-boost-terraform-loop-magic-049763fd-b681-4d7b-b0ee-96d5763be310)

---

### liam-hq/liam

📊 **FAUN·dev() popularity score**: 41/100

⭐ **GitHub stars**: 4584

**Description**: Automatically generates beautiful and easy-to-read ER diagrams from your database.

**URL**: https://github.com/liam-hq/liam

**Latest appearance**: [DevOpsLinks Issue #471 - The SE Identity Crisis, K8s The Hard Way and The Best AI for Coding in 2025](https://factory.faun.dev/newsletters/i/the-se-identity-crisis-k8s-the-hard-way-and-the-best-ai-for-coding-in-2025-0e4983ac-8e70-4da7-97dc-554179727fee)

---

### ravikiranvm/aws-finops-dashboard

📊 **FAUN·dev() popularity score**: 37/100

⭐ **GitHub stars**: 1003

**Description**: A terminal-based AWS cost and resource dashboard built with Python and the Rich library. It provides an overview of AWS spend by account, service-level breakdowns, budget tracking, and EC2 instance summaries.

**URL**: https://github.com/ravikiranvm/aws-finops-dashboard

**Latest appearance**: [DevOpsLinks Issue #475 - AI Agents Take Over DevOps, Debian Debates Ethics, and SFTP vs FTPS Showdown](https://factory.faun.dev/newsletters/i/ai-agents-take-over-devops-debian-debates-ethics-and-sftp-vs-ftps-showdown-3662a2ca-7a23-48be-9553-01781210558a)

---

### openai/codex

📊 **FAUN·dev() popularity score**: 37/100

⭐ **GitHub stars**: 54886

**Description**: Lightweight coding agent that runs in your terminal

**URL**: https://github.com/openai/codex

**Latest appearance**: [Kala Issue #498 - The New OpenAI Apps SDK - Building Apps Inside ChatGPT](https://factory.faun.dev/newsletters/i/the-new-openai-apps-sdk-building-apps-inside-chatgpt-71f777c1-15b8-449e-9d9a-76677b389155)

---

### fleetdm/fleet

📊 **FAUN·dev() popularity score**: 36/100

⭐ **GitHub stars**: 5868

**Description**: Open-source platform for IT, security, and infrastructure teams. (Linux, macOS, Chrome, Windows, cloud, data center)

**URL**: https://github.com/fleetdm/fleet

**Latest appearance**: [DevOpsLinks Issue #471 - The SE Identity Crisis, K8s The Hard Way and The Best AI for Coding in 2025](https://factory.faun.dev/newsletters/i/the-se-identity-crisis-k8s-the-hard-way-and-the-best-ai-for-coding-in-2025-0e4983ac-8e70-4da7-97dc-554179727fee)

---

### NVIDIA/KAI-Scheduler

📊 **FAUN·dev() popularity score**: 35/100

⭐ **GitHub stars**: 1043

**Description**: KAI Scheduler is an open source Kubernetes Native scheduler for AI workloads at large scale

**URL**: https://github.com/NVIDIA/KAI-Scheduler

**Latest appearance**: [Kala Issue #472 - Sec-Gemini Strikes, CUAs Rise, and Llama 4 Leads the AI Charge](https://factory.faun.dev/newsletters/i/sec-gemini-strikes-cuas-rise-and-llama-4-leads-the-ai-charge-3978a25a-2dbd-4852-b7fb-bab174160895)

---

### InftyAI/Awesome-LLMOps

📊 **FAUN·dev() popularity score**: 34/100

⭐ **GitHub stars**: 180

**Description**: An awesome & curated list of best LLMOps tools.

**URL**: https://github.com/InftyAI/Awesome-LLMOps

**Latest appearance**: [DevOpsLinks Issue #469 - Scaling Prometheus, The State of FinOps and Multi-tenancy in 2025](https://factory.faun.dev/newsletters/i/scaling-prometheus-the-state-of-finops-and-multi-tenancy-in-2025-c03c7b65-1290-40eb-8775-5ed87ae7b276)

---

### basecamp/omarchy

📊 **FAUN·dev() popularity score**: 34/100

⭐ **GitHub stars**: 18690

**Description**: Opinionated Arch/Hyprland Setup

**URL**: https://github.com/basecamp/omarchy

**Latest appearance**: [VarBear Issue #494 - Are Senior Devs Becoming AI Babysitters? Why Many Say It Works](https://factory.faun.dev/newsletters/i/are-senior-devs-becoming-ai-babysitters-why-many-say-it-works-0f30e69b-f8cd-4851-bed8-e38f25060afe)

---

### modelcontextprotocol/modelcontextprotocol

📊 **FAUN·dev() popularity score**: 32/100

⭐ **GitHub stars**: 6744

**Description**: Specification and documentation for the Model Context Protocol

**URL**: https://github.com/modelcontextprotocol/modelcontextprotocol

**Latest appearance**: [Kala Issue #477 - AI at Scale: Saudi Supercomputers, GPU Giants & Serverless Agents](https://factory.faun.dev/newsletters/i/ai-at-scale-saudi-supercomputers-gpu-giants-serverless-agents-799db520-cbb4-48ce-9e56-6e9954988371)

---

### dockur/windows-arm

📊 **FAUN·dev() popularity score**: 32/100

⭐ **GitHub stars**: 2020

**Description**: Windows for ARM in a Docker container.

**URL**: https://github.com/dockur/windows-arm

**Latest appearance**: [Kaptain Issue #470 - Every Pod Eviction Explained, Critical Ingress-nginx CVE and AI-Driven Kubernetes](https://factory.faun.dev/newsletters/i/every-pod-eviction-explained-critical-ingress-nginx-cve-and-ai-driven-kubernetes-345b9506-6479-4057-aa98-e8f1428edfd2)

---

### charlax/professional-programming

📊 **FAUN·dev() popularity score**: 30/100

⭐ **GitHub stars**: 50039

**Description**: A collection of learning resources for curious software engineers

**URL**: https://github.com/charlax/professional-programming

**Latest appearance**: [DevOpsLinks Issue #470 - VMware Sues Siemens, The Sociotechnical Reality Engineer and Handling Billions of Serverless Invocations](https://factory.faun.dev/newsletters/i/vmware-sues-siemens-the-sociotechnical-reality-engineer-and-handling-billions-of-serverless-invocations-645302a2-83d2-401e-ba98-e7663b022175)

---

### MrLesk/Backlog.md

📊 **FAUN·dev() popularity score**: 30/100

⭐ **GitHub stars**: 4283

**Description**: A tool for managing project collaboration between humans and AI Agents in a git ecosystem

**URL**: https://github.com/MrLesk/Backlog.md

**Latest appearance**: [DevOpsLinks Issue #485 - Securing Cloud with Terraform, Inside Netflix’s Observability System & Tudum Architecture](https://factory.faun.dev/newsletters/i/securing-cloud-with-terraform-inside-netflixs-observability-system-tudum-architecture-6bb50d3e-d4e2-43f4-b36e-7c578fa2f2cd)

---

### bytedance/UI-TARS-desktop

📊 **FAUN·dev() popularity score**: 30/100

⭐ **GitHub stars**: 20228

**Description**: A GUI Agent application based on UI-TARS(Vision-Language Model) that allows you to control your computer using natural language.

**URL**: https://github.com/bytedance/UI-TARS-desktop

**Latest appearance**: [Kala Issue #479 - Google I/O 100, OpenAI’s Smartest Model Refuses Shutdown, and the Prompt That Breaks LLMs](https://factory.faun.dev/newsletters/i/google-io-100-openais-smartest-model-refuses-shutdown-and-the-prompt-that-breaks-llms-d21e8318-d2e3-4803-be1d-f45b1cdc44cf)

---

### von-development/awesome-LangGraph

📊 **FAUN·dev() popularity score**: 29/100

⭐ **GitHub stars**: 1389

**Description**: A curated list of awesome projects, resources, and tools for building stateful, multi-actor applications with LangGraph

**URL**: https://github.com/von-development/awesome-LangGraph

**Latest appearance**: [Kala Issue #471 - Invisible AI for Interviews, Llama 4 Herd and OpenAI’s Worst Nightmare](https://factory.faun.dev/newsletters/i/invisible-ai-for-interviews-llama-4-herd-and-openais-worst-nightmare-48b8569f-db23-41af-843e-bbf510717240)

---

### GoogleCloudPlatform/agent-starter-pack

📊 **FAUN·dev() popularity score**: 27/100

⭐ **GitHub stars**: 5330

**Description**: A collection of production-ready Generative AI Agent templates built for Google Cloud. It accelerates development by providing a holistic, production-ready solution, addressing common challenges (Deployment & Operations, Evaluation, Customization, Observability) in building and deploying GenAI agents.

**URL**: https://github.com/GoogleCloudPlatform/agent-starter-pack

**Latest appearance**: [Kala Issue #477 - AI at Scale: Saudi Supercomputers, GPU Giants & Serverless Agents](https://factory.faun.dev/newsletters/i/ai-at-scale-saudi-supercomputers-gpu-giants-serverless-agents-799db520-cbb4-48ce-9e56-6e9954988371)

---

### github/spec-kit 

📊 **FAUN·dev() popularity score**: 27/100

⭐ **GitHub stars**: 58447

**Description**: Toolkit to help you get started with Spec-Driven Development

**URL**: https://github.com/github/spec-kit

**Latest appearance**: [VarBear Issue #497 - Writing Load Balancer From Scratch In 250 Line of Code](https://factory.faun.dev/newsletters/i/writing-load-balancer-from-scratch-in-250-line-of-code-00e17752-5dea-4293-a78a-825982e031d2)

---

### automation-ai-labs/mcp-link

📊 **FAUN·dev() popularity score**: 27/100

⭐ **GitHub stars**: 588

**Description**: Seamlessly Integrate Any API with AI Agents

**URL**: https://github.com/automation-ai-labs/mcp-link

**Latest appearance**: [DevOpsLinks Issue #470 - VMware Sues Siemens, The Sociotechnical Reality Engineer and Handling Billions of Serverless Invocations](https://factory.faun.dev/newsletters/i/vmware-sues-siemens-the-sociotechnical-reality-engineer-and-handling-billions-of-serverless-invocations-645302a2-83d2-401e-ba98-e7663b022175)

---

### oraios/serena

📊 **FAUN·dev() popularity score**: 27/100

⭐ **GitHub stars**: 17846

**Description**: A powerful coding agent toolkit providing semantic retrieval and editing capabilities (MCP server & other integrations)

**URL**: https://github.com/oraios/serena

**Latest appearance**: [Kala Issue #494 - OpenAI is Stealing Your Job but Giving You a New One](https://factory.faun.dev/newsletters/i/openai-is-stealing-your-job-but-giving-you-a-new-one-90aa77f3-858e-4834-909b-54e977882a6a)

---

### googleapis/genai-toolbox

📊 **FAUN·dev() popularity score**: 26/100

⭐ **GitHub stars**: 11977

**Description**: MCP Toolbox for Databases is an open source MCP server for databases.

**URL**: https://github.com/googleapis/genai-toolbox

**Latest appearance**: [VarBear Issue #485 - The Hunt for a Perfect Laptop, Best AIs For Job Seekers & Using a Foot Pedal for Vibe Coding](https://factory.faun.dev/newsletters/i/the-hunt-for-a-perfect-laptop-best-ais-for-job-seekers-using-a-foot-pedal-for-vibe-coding-0f6c5e7c-41e7-4a0f-aee8-065292fe94e7)

---

### HKUDS/Vimo

📊 **FAUN·dev() popularity score**: 26/100

⭐ **GitHub stars**: 1576

**Description**: Chat with Your Videos

**URL**: https://github.com/HKUDS/Vimo

**Latest appearance**: [Kala Issue #489 - 100-Agent Research Swarms Emerge](https://factory.faun.dev/newsletters/i/100-agent-research-swarms-emerge-b35a83f8-dcd6-46f5-b81b-d1a1d05908f7)

---

### VersusControl/versus-incident

📊 **FAUN·dev() popularity score**: 26/100

⭐ **GitHub stars**: 376

**Description**: An open-source incident management tool supporting multi-channel alerting, customizable messages, and on-call integrations.

**URL**: https://github.com/VersusControl/versus-incident

**Latest appearance**: [DevOpsLinks Issue #469 - Scaling Prometheus, The State of FinOps and Multi-tenancy in 2025](https://factory.faun.dev/newsletters/i/scaling-prometheus-the-state-of-finops-and-multi-tenancy-in-2025-c03c7b65-1290-40eb-8775-5ed87ae7b276)

---

### ripienaar/free-for-dev

📊 **FAUN·dev() popularity score**: 26/100

⭐ **GitHub stars**: 116599

**Description**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

**URL**: https://github.com/ripienaar/free-for-dev

**Latest appearance**: [DevOpsLinks Issue #483 - Broadcom Bullying Enterprises with VMware Audits, Cloudflare Blocks Largest DDoS Attack & Agentic DevOps](https://factory.faun.dev/newsletters/i/broadcom-bullying-enterprises-with-vmware-audits-cloudflare-blocks-largest-ddos-attack-agentic-devops-3b78d2dc-942d-4f7a-a6c0-845f6af52b03)

---

### jumpserver/jumpserver

📊 **FAUN·dev() popularity score**: 25/100

⭐ **GitHub stars**: 29296

**Description**: JumpServer is an open-source Privileged Access Management (PAM) tool that provides DevOps and IT teams with on-demand and secure access to SSH, RDP, Kubernetes, Database and RemoteApp endpoints through a web browser.

**URL**: https://github.com/jumpserver/jumpserver

**Latest appearance**: [DevOpsLinks Issue #477 - OpenAI’s UAE Megacenter, CI/CD Speed Boost, & Terraform Loop Magic](https://factory.faun.dev/newsletters/i/openais-uae-megacenter-cicd-speed-boost-terraform-loop-magic-049763fd-b681-4d7b-b0ee-96d5763be310)

---

### karpathy/rendergit

📊 **FAUN·dev() popularity score**: 25/100

⭐ **GitHub stars**: 1982

**Description**: Render any git repo into a single static HTML page for humans or LLMs

**URL**: https://github.com/karpathy/rendergit

**Latest appearance**: [Kala Issue #491 - Code a MCP-powered Agent in ~70 Lines of Code](https://factory.faun.dev/newsletters/i/code-a-mcp-powered-agent-in-70-lines-of-code-a4ed34b1-cad5-46ef-a78c-48cd9e00df98)

---

### Zie619/n8n-workflows

📊 **FAUN·dev() popularity score**: 25/100

⭐ **GitHub stars**: 48700

**Description**: A professionally organized collection of 2,057 n8n workflows with a lightning-fast documentation system that provides instant search, analysis, and browsing capabilities.

**URL**: https://github.com/Zie619/n8n-workflows

**Latest appearance**: [Kala Issue #499 - OpenAI Needs $400 Billion. This Year!](https://factory.faun.dev/newsletters/i/openai-needs-400-billion-this-year-d25f6fe3-798b-4961-a0fc-0fdfe4df67d5)

---

### google/yamlfmt

📊 **FAUN·dev() popularity score**: 24/100

⭐ **GitHub stars**: 1662

**Description**: An extensible command line tool or library to format yaml files.

**URL**: https://github.com/google/yamlfmt

**Latest appearance**: [Kaptain Issue #492 - AI Architecture Upends Computing: Can Kubernetes Remain The AI-Native Platform?](https://factory.faun.dev/newsletters/i/ai-architecture-upends-computing-can-kubernetes-remain-the-ai-native-platform-84f44ca1-b1e2-4a55-86f4-1229e9d380a6)

---

### eduardoagarcia/shef

📊 **FAUN·dev() popularity score**: 24/100

⭐ **GitHub stars**: 278

**Description**: Shef is a powerful CLI framework for cooking up advanced shell recipes.

**URL**: https://github.com/eduardoagarcia/shef

**Latest appearance**: [DevOpsLinks Issue #470 - VMware Sues Siemens, The Sociotechnical Reality Engineer and Handling Billions of Serverless Invocations](https://factory.faun.dev/newsletters/i/vmware-sues-siemens-the-sociotechnical-reality-engineer-and-handling-billions-of-serverless-invocations-645302a2-83d2-401e-ba98-e7663b022175)

---

### zxh326/kite

📊 **FAUN·dev() popularity score**: 23/100

⭐ **GitHub stars**: 1969

**Description**: A modern, lightweight Kubernetes dashboard

**URL**: https://github.com/zxh326/kite

**Latest appearance**: [Kaptain Issue #484 - K8s FinOps 2.0 AI Cost Optimization, K8s Usage Insights & K8s Complexity Killer](https://factory.faun.dev/newsletters/i/k8s-finops-20-ai-cost-optimization-k8s-usage-insights-k8s-complexity-killer-5b81ab7f-bcd2-41bf-8d20-1fcb93072f12)

---

### manaskamal/XenevaOS

📊 **FAUN·dev() popularity score**: 22/100

⭐ **GitHub stars**: 630

**Description**: The Xeneva Operating System

**URL**: https://github.com/manaskamal/XenevaOS

**Latest appearance**: [DevOpsLinks Issue #483 - Broadcom Bullying Enterprises with VMware Audits, Cloudflare Blocks Largest DDoS Attack & Agentic DevOps](https://factory.faun.dev/newsletters/i/broadcom-bullying-enterprises-with-vmware-audits-cloudflare-blocks-largest-ddos-attack-agentic-devops-3b78d2dc-942d-4f7a-a6c0-845f6af52b03)

---

### azurekid/blackcat

📊 **FAUN·dev() popularity score**: 21/100

⭐ **GitHub stars**: 152

**Description**: BlackCat is a PowerShell module designed to validate the security of Microsoft Azure. It provides a set of functions to identify potential security holes.

**URL**: https://github.com/azurekid/blackcat

**Latest appearance**: [DevOpsLinks Issue #471 - The SE Identity Crisis, K8s The Hard Way and The Best AI for Coding in 2025](https://factory.faun.dev/newsletters/i/the-se-identity-crisis-k8s-the-hard-way-and-the-best-ai-for-coding-in-2025-0e4983ac-8e70-4da7-97dc-554179727fee)

---

### Flux159/mcp-server-kubernetes

📊 **FAUN·dev() popularity score**: 21/100

⭐ **GitHub stars**: 1232

**Description**: MCP Server for kubernetes management commands

**URL**: https://github.com/Flux159/mcp-server-kubernetes

**Latest appearance**: [Kaptain Issue #475 - Kubernetes 1.33 Features, EKS Auto-Heals, and Uber Goes All-In on K8s](https://factory.faun.dev/newsletters/i/kubernetes-133-features-eks-auto-heals-and-uber-goes-all-in-on-k8s-3e955dff-8e41-4caa-9f44-fe861d7921ea)

---

### hcengineering/platform

📊 **FAUN·dev() popularity score**: 20/100

⭐ **GitHub stars**: 23998

**Description**: Huly — All-in-One Project Management Platform (alternative to Linear, Jira, Slack, Notion, Motion)

**URL**: https://github.com/hcengineering/platform

**Latest appearance**: [DevOpsLinks Issue #470 - VMware Sues Siemens, The Sociotechnical Reality Engineer and Handling Billions of Serverless Invocations](https://factory.faun.dev/newsletters/i/vmware-sues-siemens-the-sociotechnical-reality-engineer-and-handling-billions-of-serverless-invocations-645302a2-83d2-401e-ba98-e7663b022175)

---

### alibaba/spring-ai-alibaba

📊 **FAUN·dev() popularity score**: 20/100

⭐ **GitHub stars**: 7661

**Description**: Agentic AI Framework for Java Developers

**URL**: https://github.com/alibaba/spring-ai-alibaba

**Latest appearance**: [Kala Issue #479 - Google I/O 100, OpenAI’s Smartest Model Refuses Shutdown, and the Prompt That Breaks LLMs](https://factory.faun.dev/newsletters/i/google-io-100-openais-smartest-model-refuses-shutdown-and-the-prompt-that-breaks-llms-d21e8318-d2e3-4803-be1d-f45b1cdc44cf)

---

### github/github-mcp-server

📊 **FAUN·dev() popularity score**: 19/100

⭐ **GitHub stars**: 25500

**Description**: GitHub's official MCP Server

**URL**: https://github.com/github/github-mcp-server

**Latest appearance**: [Kala Issue #471 - Invisible AI for Interviews, Llama 4 Herd and OpenAI’s Worst Nightmare](https://factory.faun.dev/newsletters/i/invisible-ai-for-interviews-llama-4-herd-and-openais-worst-nightmare-48b8569f-db23-41af-843e-bbf510717240)

---

### edoardottt/cariddi

📊 **FAUN·dev() popularity score**: 19/100

⭐ **GitHub stars**: 2915

**Description**: Take a list of domains, crawl urls and scan for endpoints, secrets, api keys, file extensions, tokens and more

**URL**: https://github.com/edoardottt/cariddi

**Latest appearance**: [DevOpsLinks Issue #477 - OpenAI’s UAE Megacenter, CI/CD Speed Boost, & Terraform Loop Magic](https://factory.faun.dev/newsletters/i/openais-uae-megacenter-cicd-speed-boost-terraform-loop-magic-049763fd-b681-4d7b-b0ee-96d5763be310)

---

### jnesss/bpfview

📊 **FAUN·dev() popularity score**: 19/100

⭐ **GitHub stars**: 32

**Description**: BPFView: Process and Network Activity Correlation

**URL**: https://github.com/jnesss/bpfview

**Latest appearance**: [DevOpsLinks Issue #481 - AWS AI Agentic Coding Experience, Uber's Multi-Cloud Secrets Management & DevOps Tools Cryptojacking](https://factory.faun.dev/newsletters/i/aws-ai-agentic-coding-experience-ubers-multi-cloud-secrets-management-devops-tools-cryptojacking-83862f68-3e1c-4840-973e-9be9d399a40b)

---

### RchGrav/claudebox

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 756

**Description**: The Ultimate Claude Code Docker Development Environment - Run Claude AI's coding assistant in a fully containerized, reproducible environment with pre-configured development profiles.

**URL**: https://github.com/RchGrav/claudebox

**Latest appearance**: [Kaptain Issue #487 - 🔍 10 Kubernetes Autoscaling Traps That Are Wasting Your Budget](https://factory.faun.dev/newsletters/i/10-kubernetes-autoscaling-traps-that-are-wasting-your-budget-2cf779c1-39bb-4f1d-8fe9-150ff83b97ae)

---

### stacklok/toolhive

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 1472

**Description**: ToolHive makes deploying MCP servers easy, secure and fun

**URL**: https://github.com/stacklok/toolhive

**Latest appearance**: [VarBear Issue #498 - OpenAI Agent Builder - A Complete Guide](https://factory.faun.dev/newsletters/i/openai-agent-builder-a-complete-guide-3dcba5dd-18d0-457f-b5f9-1d161b136a01)

---

### ByTheHugo/kubeboard

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 7

**Description**: KubeBoard dishes out a stylish Python/Flask GUI to reveal Kubernetes ingresses in all their glory. It comes loaded with customizations and dynamic updates to keep your dashboard snappy and alive.

**URL**: https://github.com/ByTheHugo/kubeboard

**Latest appearance**: [Kaptain Issue #473 - Tanzu Ditches K8s, Docker Runs Models Locally, and Agents Take Over Ops](https://factory.faun.dev/newsletters/i/tanzu-ditches-k8s-docker-runs-models-locally-and-agents-take-over-ops-89b6a0bd-5c10-41f2-b49f-3aec2d5207f3)

---

### sgoedecke/gh-standup

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 94

**Description**: A CLI extension for generating an AI-assisted standup report

**URL**: https://github.com/sgoedecke/gh-standup

**Latest appearance**: [DevOpsLinks Issue #485 - Securing Cloud with Terraform, Inside Netflix’s Observability System & Tudum Architecture](https://factory.faun.dev/newsletters/i/securing-cloud-with-terraform-inside-netflixs-observability-system-tudum-architecture-6bb50d3e-d4e2-43f4-b36e-7c578fa2f2cd)

---

### aelassas/servy

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 991

**Description**: Turn Any App into a Native Windows Service — Open-Source Alternative to NSSM & FireDaemon

**URL**: https://github.com/aelassas/servy

**Latest appearance**: [DevOpsLinks Issue #491 - Can LLMs Replace On-Call SREs Today?](https://factory.faun.dev/newsletters/i/can-llms-replace-on-call-sres-today-1fa880fc-1b9a-4299-b25e-d7fbcf05bc18)

---

### headlamp-k8s/headlamp

📊 **FAUN·dev() popularity score**: 18/100

⭐ **GitHub stars**: 5226

**Description**: A Kubernetes web UI that is fully-featured, user-friendly and extensible

**URL**: https://github.com/headlamp-k8s/headlamp

**Latest appearance**: [Kaptain Issue #468 - Hardening Docker Networking, 'Please Start a Cluster for Me,' and WebAssembly on K8s](https://factory.faun.dev/newsletters/i/hardening-docker-networking-please-start-a-cluster-for-me-and-webassembly-on-k8s-46742c17-103a-4500-b9d2-900aa93cb7d0)

---

### obeli-sk/obelisk

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 394

**Description**: Deterministic workflow engine

**URL**: https://github.com/obeli-sk/obelisk

**Latest appearance**: [DevOpsLinks Issue #477 - OpenAI’s UAE Megacenter, CI/CD Speed Boost, & Terraform Loop Magic](https://factory.faun.dev/newsletters/i/openais-uae-megacenter-cicd-speed-boost-terraform-loop-magic-049763fd-b681-4d7b-b0ee-96d5763be310)

---

### mindverse/Second-Me

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 14833

**Description**: Train your AI self, amplify you, bridge the world

**URL**: https://github.com/mindverse/Second-Me

**Latest appearance**: [Kala Issue #469 - The DeepSeek R1 Tutorial, FAANG job will be Automated by 2026 and Lean AI Native Companies](https://factory.faun.dev/newsletters/i/the-deepseek-r1-tutorial-faang-job-will-be-automated-by-2026-and-lean-ai-native-companies-7ca72177-c782-4dbc-bd35-57273fd9c6c4)

---

### log-forge/logforge

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 277

**Description**: Like Dozzle but with alerts and a one command set-up

**URL**: https://github.com/log-forge/logforge

**Latest appearance**: [Kaptain Issue #484 - K8s FinOps 2.0 AI Cost Optimization, K8s Usage Insights & K8s Complexity Killer](https://factory.faun.dev/newsletters/i/k8s-finops-20-ai-cost-optimization-k8s-usage-insights-k8s-complexity-killer-5b81ab7f-bcd2-41bf-8d20-1fcb93072f12)

---

### stacklok/toolhive

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 1472

**Description**: ToolHive makes deploying MCP servers easy, secure and fun

**URL**: https://github.com/stacklok/toolhive

**Latest appearance**: [Kala Issue #499 - OpenAI Needs $400 Billion. This Year!](https://factory.faun.dev/newsletters/i/openai-needs-400-billion-this-year-d25f6fe3-798b-4961-a0fc-0fdfe4df67d5)

---

### psviderski/unregistry

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 4417

**Description**: Push docker images directly to remote servers without an external registry

**URL**: https://github.com/psviderski/unregistry

**Latest appearance**: [DevOpsLinks Issue #483 - Broadcom Bullying Enterprises with VMware Audits, Cloudflare Blocks Largest DDoS Attack & Agentic DevOps](https://factory.faun.dev/newsletters/i/broadcom-bullying-enterprises-with-vmware-audits-cloudflare-blocks-largest-ddos-attack-agentic-devops-3b78d2dc-942d-4f7a-a6c0-845f6af52b03)

---

### portainer/kubesolo

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 424

**Description**: Ultra-lightweight Kubernetes

**URL**: https://github.com/portainer/kubesolo

**Latest appearance**: [Kaptain Issue #482 - AWS EKS Flaw Exposes Credentials, Kubernetes 1.33 Resizing Pods & F5 AI Innovations](https://factory.faun.dev/newsletters/i/aws-eks-flaw-exposes-credentials-kubernetes-133-resizing-pods-f5-ai-innovations-0c0e0f57-df32-459d-9f59-07980141bcb4)

---

### xpipe-io/xpipe

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 12199

**Description**: Access your entire server infrastructure from your local desktop

**URL**: https://github.com/xpipe-io/xpipe

**Latest appearance**: [DevOpsLinks Issue #469 - Scaling Prometheus, The State of FinOps and Multi-tenancy in 2025](https://factory.faun.dev/newsletters/i/scaling-prometheus-the-state-of-finops-and-multi-tenancy-in-2025-c03c7b65-1290-40eb-8775-5ed87ae7b276)

---

### automation-ai-labs/mcp-link

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 588

**Description**: Seamlessly Integrate Any API with AI Agents

**URL**: https://github.com/automation-ai-labs/mcp-link

**Latest appearance**: [Kala Issue #471 - Invisible AI for Interviews, Llama 4 Herd and OpenAI’s Worst Nightmare](https://factory.faun.dev/newsletters/i/invisible-ai-for-interviews-llama-4-herd-and-openais-worst-nightmare-48b8569f-db23-41af-843e-bbf510717240)

---

### winapps-org/winapps

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 13652

**Description**: Run Windows apps such as Microsoft Office/Adobe in Linux (Ubuntu/Fedora) and GNOME/KDE as if they were a part of the native OS, including Nautilus integration.

**URL**: https://github.com/winapps-org/winapps

**Latest appearance**: [DevOpsLinks Issue #494 - The 5 Sneaky AWS Cost Traps](https://factory.faun.dev/newsletters/i/the-5-sneaky-aws-cost-traps-cf63c299-5fa9-4e72-b9f3-c8a472af215f)

---

### serkanh/sre-bot

📊 **FAUN·dev() popularity score**: 17/100

⭐ **GitHub stars**: 37

**Description**: A Google Agent Development Kit (ADK) powered assistant designed to help Site Reliability Engineers (SREs) with operational tasks and monitoring, particularly focused on Kubernetes interactions.

**URL**: https://github.com/serkanh/sre-bot

**Latest appearance**: [Kaptain Issue #477 - Kubernetes 1.33 Powers Up, Azure Functions Join ACA & OrbStack Challenges Docker](https://factory.faun.dev/newsletters/i/kubernetes-133-powers-up-azure-functions-join-aca-orbstack-challenges-docker-cb8c4d6e-cc0a-44c5-9b01-cc6d69494c7b)

---

### jdepoix/youtube-transcript-api

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 6635

**Description**: This is a python API which allows you to get the transcript/subtitles for a given YouTube video. It also works for automatically generated subtitles and it does not require an API key nor a headless browser, like other selenium based solutions do!

**URL**: https://github.com/jdepoix/youtube-transcript-api

**Latest appearance**: [Kala Issue #487 - 🧠 Claude Is Replacing Developers at Anthropic — No Code Needed](https://factory.faun.dev/newsletters/i/claude-is-replacing-developers-at-anthropic-no-code-needed-77a8a999-d427-4f31-bd7d-54c26767a69a)

---

### karpathy/nanochat

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 39436

**Description**: The best ChatGPT that $100 can buy.

**URL**: https://github.com/karpathy/nanochat

**Latest appearance**: [Kala Issue #501 - CUDA Goes Mainstream: NVIDIA and Red Hat Bring GPU Power to Every Linux Distro](https://factory.faun.dev/newsletters/i/cuda-goes-mainstream-nvidia-and-red-hat-bring-gpu-power-to-every-linux-distro-d8186858-fe56-4103-9f23-3c15b769efea)

---

### richardscollin/tmux-rs

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 772

**Description**: A Rust port of tmux

**URL**: https://github.com/richardscollin/tmux-rs

**Latest appearance**: [DevOpsLinks Issue #485 - Securing Cloud with Terraform, Inside Netflix’s Observability System & Tudum Architecture](https://factory.faun.dev/newsletters/i/securing-cloud-with-terraform-inside-netflixs-observability-system-tudum-architecture-6bb50d3e-d4e2-43f4-b36e-7c578fa2f2cd)

---

### charmbracelet/crush

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 16478

**Description**: The glamourous AI coding agent for your favourite terminal

**URL**: https://github.com/charmbracelet/crush

**Latest appearance**: [DevOpsLinks Issue #490 - AWS Deleted my 10-year Account and all Data Without Warning](https://factory.faun.dev/newsletters/i/aws-deleted-my-10-year-account-and-all-data-without-warning-546a3fb1-d885-43d9-910e-188f454f547b)

---

### kirodotdev/Kiro

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 2487

**Description**: Kiro is an agentic IDE that works alongside you from prototype to production.

**URL**: https://github.com/kirodotdev/Kiro

**Latest appearance**: [Kala Issue #486 - Zuck's AI Beast, Rethinking RAG & Self-Evolving Knowledge Graphs](https://factory.faun.dev/newsletters/i/zucks-ai-beast-rethinking-rag-self-evolving-knowledge-graphs-eec2ea36-f6bb-4c26-a8fd-c219a67eae3e)

---

### kaito-project/kaito

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 852

**Description**: Kubernetes AI Toolchain Operator

**URL**: https://github.com/kaito-project/kaito

**Latest appearance**: [DevOpsLinks Issue #483 - Broadcom Bullying Enterprises with VMware Audits, Cloudflare Blocks Largest DDoS Attack & Agentic DevOps](https://factory.faun.dev/newsletters/i/broadcom-bullying-enterprises-with-vmware-audits-cloudflare-blocks-largest-ddos-attack-agentic-devops-3b78d2dc-942d-4f7a-a6c0-845f6af52b03)

---

### chains-project/goleash

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 18

**Description**: Runtime enforcement of software supply chain capabilities in Go

**URL**: https://github.com/chains-project/goleash

**Latest appearance**: [DevOpsLinks Issue #481 - AWS AI Agentic Coding Experience, Uber's Multi-Cloud Secrets Management & DevOps Tools Cryptojacking](https://factory.faun.dev/newsletters/i/aws-ai-agentic-coding-experience-ubers-multi-cloud-secrets-management-devops-tools-cryptojacking-83862f68-3e1c-4840-973e-9be9d399a40b)

---

### ServBay/ServBay

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 319

**Description**: ServBay is an all-in-one localized web development environment that simplifies and accelerates your web projects.

**URL**: https://github.com/ServBay/ServBay

**Latest appearance**: [DevOpsLinks Issue #482 - Weaponizing Dependabot Attacks, GitOps 2025 Transformations & Rethinking Automatic Rollbacks](https://factory.faun.dev/newsletters/i/weaponizing-dependabot-attacks-gitops-2025-transformations-rethinking-automatic-rollbacks-e9d2aae6-7481-4bb1-84b9-8bae43702b38)

---

### charmbracelet/crush

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 16478

**Description**: The glamourous AI coding agent for your favourite terminal

**URL**: https://github.com/charmbracelet/crush

**Latest appearance**: [VarBear Issue #489 - Google Releases AI Agent Jules for Programming](https://factory.faun.dev/newsletters/i/google-releases-ai-agent-jules-for-programming-97234cc6-2a36-4548-8bfc-769ee712a3b8)

---

### Linbreux/FlockRunner

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 3

**Description**: YAML command executor

**URL**: https://github.com/Linbreux/FlockRunner

**Latest appearance**: [DevOpsLinks Issue #482 - Weaponizing Dependabot Attacks, GitOps 2025 Transformations & Rethinking Automatic Rollbacks](https://factory.faun.dev/newsletters/i/weaponizing-dependabot-attacks-gitops-2025-transformations-rethinking-automatic-rollbacks-e9d2aae6-7481-4bb1-84b9-8bae43702b38)

---

### sst/models.dev

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 1912

**Description**: An open-source database of AI models.

**URL**: https://github.com/sst/models.dev

**Latest appearance**: [Kala Issue #484 - Google's A2A Protocol, Gemma 3n's Novel Techniques & The Ultimate LLM Evaluation Guide](https://factory.faun.dev/newsletters/i/googles-a2a-protocol-gemma-3ns-novel-techniques-the-ultimate-llm-evaluation-guide-8a409683-3d65-4d2d-b670-933dfe923a9e)

---

### roottusk/vapi

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 1319

**Description**: vAPI is Vulnerable Adversely Programmed Interface which is Self-Hostable API that mimics OWASP API Top 10 scenarios through Exercises.

**URL**: https://github.com/roottusk/vapi

**Latest appearance**: [DevOpsLinks Issue #479 - Why Are There So Many Databases, Scaling Azure Microservices and Improving EC2 Boot Time](https://factory.faun.dev/newsletters/i/why-are-there-so-many-databases-scaling-azure-microservices-and-improving-ec2-boot-time-ef806c91-c305-4f54-b601-c5820b316037)

---

### simular-ai/Agent-S

📊 **FAUN·dev() popularity score**: 16/100

⭐ **GitHub stars**: 9178

**Description**: An open agentic framework that uses computers like a human

**URL**: https://github.com/simular-ai/Agent-S

**Latest appearance**: [DevOpsLinks Issue #476 - Cloud Repatriation at 37signals, Rebuilding Kafka, & GPT-Powered Ansible Automation](https://factory.faun.dev/newsletters/i/cloud-repatriation-at-37signals-rebuilding-kafka-gpt-powered-ansible-automation-601126b3-ac01-434f-8fae-2a83ed3de4e4)

---

### Kilo-Org/kilocode

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 13579

**Description**: Open Source AI coding assistant for planning, building, and fixing code. We're a superset of Roo, Cline, and our own features.

**URL**: https://github.com/Kilo-Org/kilocode

**Latest appearance**: [VarBear Issue #486 - Asynchrony is not Concurrency, Scalability is not Performance & Crawling a Billion Pages in 24h,](https://factory.faun.dev/newsletters/i/asynchrony-is-not-concurrency-scalability-is-not-performance-crawling-a-billion-pages-in-24h-9d4aa002-8f28-4de3-b466-4c5fedfd452f)

---

### paloaltodatabases/sequor

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 88

**Description**: Build complete API integrations with YAML and SQL. Rapid development without vendor lock-in and per-row costs.

**URL**: https://github.com/paloaltodatabases/sequor

**Latest appearance**: [DevOpsLinks Issue #482 - Weaponizing Dependabot Attacks, GitOps 2025 Transformations & Rethinking Automatic Rollbacks](https://factory.faun.dev/newsletters/i/weaponizing-dependabot-attacks-gitops-2025-transformations-rethinking-automatic-rollbacks-e9d2aae6-7481-4bb1-84b9-8bae43702b38)

---

### tooka-org/cli

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 10

**Description**: A fast, rule-based CLI tool for organizing files.

**URL**: https://github.com/Benji377/tooka

**Latest appearance**: [DevOpsLinks Issue #482 - Weaponizing Dependabot Attacks, GitOps 2025 Transformations & Rethinking Automatic Rollbacks](https://factory.faun.dev/newsletters/i/weaponizing-dependabot-attacks-gitops-2025-transformations-rethinking-automatic-rollbacks-e9d2aae6-7481-4bb1-84b9-8bae43702b38)

---

### kubermatic/fubectl

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 980

**Description**: Reduces repetitive interactions with kubectl

**URL**: https://github.com/kubermatic/fubectl

**Latest appearance**: [DevOpsLinks Issue #495 - Prometheus - Managing 80M Metrics Smoothly](https://factory.faun.dev/newsletters/i/prometheus-managing-80m-metrics-smoothly-5823ecef-570b-48bd-9108-c57b15f541f2)

---

### a0xAi/kubeve

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 28

**Description**: Human Friendly Way to look for Kubernetes Events

**URL**: https://github.com/a0xAi/kubeve

**Latest appearance**: [Kaptain Issue #477 - Kubernetes 1.33 Powers Up, Azure Functions Join ACA & OrbStack Challenges Docker](https://factory.faun.dev/newsletters/i/kubernetes-133-powers-up-azure-functions-join-aca-orbstack-challenges-docker-cb8c4d6e-cc0a-44c5-9b01-cc6d69494c7b)

---

### platform-engineering-labs/formae

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 639

**Description**: Infrastructure-as-Code Platform Built for the Future

**URL**: https://github.com/platform-engineering-labs/formae

**Latest appearance**: [DevOpsLinks Issue #503 - Terraform vs. Pulumi vs. Crossplane](https://factory.faun.dev/newsletters/i/terraform-vs-pulumi-vs-crossplane-b37c82fe-5e5e-42eb-8a92-241f52115c8e)

---

### anthropics/prompt-eng-interactive-tutorial

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 27866

**Description**: Anthropic's Interactive Prompt Engineering Tutorial

**URL**: https://github.com/anthropics/prompt-eng-interactive-tutorial

**Latest appearance**: [Kala Issue #487 - 🧠 Claude Is Replacing Developers at Anthropic — No Code Needed](https://factory.faun.dev/newsletters/i/claude-is-replacing-developers-at-anthropic-no-code-needed-77a8a999-d427-4f31-bd7d-54c26767a69a)

---

### gamemann/XDP-Proxy

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 255

**Description**: A stateless, high-performance NAT-like proxy that attaches to the XDP hook in the Linux kernel using (e)BPF for fast packet processing. This proxy forwards packets based on configurable rules and performs source-port mapping, similar to IPTables and NFTables.

**URL**: https://github.com/gamemann/XDP-Proxy

**Latest appearance**: [DevOpsLinks Issue #481 - AWS AI Agentic Coding Experience, Uber's Multi-Cloud Secrets Management & DevOps Tools Cryptojacking](https://factory.faun.dev/newsletters/i/aws-ai-agentic-coding-experience-ubers-multi-cloud-secrets-management-devops-tools-cryptojacking-83862f68-3e1c-4840-973e-9be9d399a40b)

---

### marverix/gah

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 238

**Description**: gah is a GitHub Releases app installer, that does not require sudo

**URL**: https://github.com/marverix/gah

**Latest appearance**: [DevOpsLinks Issue #469 - Scaling Prometheus, The State of FinOps and Multi-tenancy in 2025](https://factory.faun.dev/newsletters/i/scaling-prometheus-the-state-of-finops-and-multi-tenancy-in-2025-c03c7b65-1290-40eb-8775-5ed87ae7b276)

---

### EzpieCo/GetHooky

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 52

**Description**: git hooks managing with stupidity as priority

**URL**: https://github.com/ezpieco/gethooky

**Latest appearance**: [DevOpsLinks Issue #481 - AWS AI Agentic Coding Experience, Uber's Multi-Cloud Secrets Management & DevOps Tools Cryptojacking](https://factory.faun.dev/newsletters/i/aws-ai-agentic-coding-experience-ubers-multi-cloud-secrets-management-devops-tools-cryptojacking-83862f68-3e1c-4840-973e-9be9d399a40b)

---

### superdesigndev/superdesign

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 5599

**Description**: Cursor for design

**URL**: https://github.com/superdesigndev/superdesign

**Latest appearance**: [VarBear Issue #489 - Google Releases AI Agent Jules for Programming](https://factory.faun.dev/newsletters/i/google-releases-ai-agent-jules-for-programming-97234cc6-2a36-4548-8bfc-769ee712a3b8)

---

### docker/docker-language-server

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 141

**Description**: The Docker Language Server taps into Buildx for its secret sauce. Shines a light on Dockerfile vulnerabilities with Docker Scout. Running Go 1.23+? Perfect. Snag the source, unleash tests straight from Docker, and watch the magic unfold.

**URL**: https://github.com/docker/docker-language-server

**Latest appearance**: [Kaptain Issue #473 - Tanzu Ditches K8s, Docker Runs Models Locally, and Agents Take Over Ops](https://factory.faun.dev/newsletters/i/tanzu-ditches-k8s-docker-runs-models-locally-and-agents-take-over-ops-89b6a0bd-5c10-41f2-b49f-3aec2d5207f3)

---

### koogle/claudebox

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 22

**Description**: Run claude code in a container

**URL**: https://github.com/koogle/claudebox

**Latest appearance**: [DevOpsLinks Issue #483 - Broadcom Bullying Enterprises with VMware Audits, Cloudflare Blocks Largest DDoS Attack & Agentic DevOps](https://factory.faun.dev/newsletters/i/broadcom-bullying-enterprises-with-vmware-audits-cloudflare-blocks-largest-ddos-attack-agentic-devops-3b78d2dc-942d-4f7a-a6c0-845f6af52b03)

---

### okigan/awscurl

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 879

**Description**: curl-like access to AWS resources with AWS Signature Version 4 request signing.

**URL**: https://github.com/okigan/awscurl

**Latest appearance**: [DevOpsLinks Issue #471 - The SE Identity Crisis, K8s The Hard Way and The Best AI for Coding in 2025](https://factory.faun.dev/newsletters/i/the-se-identity-crisis-k8s-the-hard-way-and-the-best-ai-for-coding-in-2025-0e4983ac-8e70-4da7-97dc-554179727fee)

---

### HewlettPackard/terraschema

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 61

**Description**: Generate JSON Schema files based on a Terraform configuration

**URL**: https://github.com/HewlettPackard/terraschema

**Latest appearance**: [DevOpsLinks Issue #472 - GitHub at 20, YAML-Powered Backstage & Platform Engineering in Action](https://factory.faun.dev/newsletters/i/github-at-20-yaml-powered-backstage-platform-engineering-in-action-e36ec333-7b4c-4aae-8233-139fd26ce616)

---

### rasbt/LLMs-from-scratch

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 81917

**Description**: Implementing a ChatGPT-like LLM from scratch, step by step

**URL**: https://github.com/rasbt/LLMs-from-scratch

**Latest appearance**: [Kala Issue #499 - OpenAI Needs $400 Billion. This Year!](https://factory.faun.dev/newsletters/i/openai-needs-400-billion-this-year-d25f6fe3-798b-4961-a0fc-0fdfe4df67d5)

---

### verdaccio/verdaccio

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 17368

**Description**: A lightweight Node.js private proxy registry

**URL**: https://github.com/verdaccio/verdaccio

**Latest appearance**: [Kaptain Issue #471 - New GUI for K8s, Recyling a Smartphone into a K8s Node and How Google Will Evolve K8s in the AI Era](https://factory.faun.dev/newsletters/i/new-gui-for-k8s-recyling-a-smartphone-into-a-k8s-node-and-how-google-will-evolve-k8s-in-the-ai-era-a8cf07d3-ca22-4787-8212-b0aae95a9844)

---

### laude-institute/terminal-bench

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 1266

**Description**: A benchmark for LLMs on complicated tasks in the terminal

**URL**: https://github.com/laude-institute/terminal-bench

**Latest appearance**: [Kala Issue #495 - GitHub MCP Registry - The Fastest Way to Discover AI Tools](https://factory.faun.dev/newsletters/i/github-mcp-registry-the-fastest-way-to-discover-ai-tools-6db55679-ba54-4ffa-afec-4cef34138d46)

---

### operacle/checkcle

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 1948

**Description**: CheckCle is a self-hosted, open-source monitoring platform for seamless, real-time full-stack systems, applications, and infrastructure. It provides real-time uptime monitoring, distributed checks, incident tracking, and alerts. All deployable anywhere.

**URL**: https://github.com/operacle/checkcle

**Latest appearance**: [DevOpsLinks Issue #489 - Perplexity Accused of Using Stealth Crawlers to Bypass Robots No-Crawl](https://factory.faun.dev/newsletters/i/perplexity-accused-of-using-stealth-crawlers-to-bypass-robots-no-crawl-b1248637-d4fb-4b09-9044-088a4f6776de)

---

### sanaysarthak/git-laugh-track

📊 **FAUN·dev() popularity score**: 15/100

⭐ **GitHub stars**: 154

**Description**: A Git hook that plays a sitcom laugh track every time you commit.

**URL**: https://github.com/sanaysarthak/git-laugh-track

**Latest appearance**: [DevOpsLinks Issue #495 - Prometheus - Managing 80M Metrics Smoothly](https://factory.faun.dev/newsletters/i/prometheus-managing-80m-metrics-smoothly-5823ecef-570b-48bd-9108-c57b15f541f2)

---

### 👉 Join FAUN·dev()

If you found this list useful, there's more waiting for you on FAUN·dev().

- **[Publish your own posts](https://faun.dev/co/choose/)** and share hard-earned insights with other developers.
- **[Learn deeper](https://faun.dev/sensei)** with structured, practical content on FAUN·sensei().
- **Follow our weekly newsletters** to stay ahead in DevOps, Kubernetes, AI/ML, and programming:
  - DevOpsLinks: https://faun.dev/newsletter/devopslinks
  - Kaptain: https://faun.dev/newsletter/kaptain
  - Kala: https://faun.dev/newsletter/kala
  - VarBear: https://faun.dev/newsletter/varbear
- **[Submit and track tools](https://faun.dev/co/choose/)** you care about or build, and see how the community engages with them.
- And much more...

FAUN·dev() is built by developers, for developers. Join us today!