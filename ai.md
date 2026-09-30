# AI

## Fundamentals

- [Neural Networks (3Blue1Brown)](https://www.3blue1brown.com/topics/neural-networks)
- [Neural Networks: Zero to Hero (Karpathy)](https://karpathy.ai/zero-to-hero.html)
- [nanoGPT](https://github.com/karpathy/nanoGPT)
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [LLM Course (mlabonne)](https://github.com/mlabonne/llm-course)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)
- [smol course: fine-tuning small models](https://github.com/huggingface/smol-course)
- [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)

## Prompting and APIs

- [Claude docs](https://docs.claude.com/)
- [Tool use (Claude docs)](https://docs.claude.com/en/docs/agents-and-tools/tool-use/overview)
- [OpenAI Cookbook](https://cookbook.openai.com/)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

## Agents

- [Building effective agents (Anthropic)](https://www.anthropic.com/engineering/building-effective-agents)
- [Effective context engineering for AI agents (Anthropic)](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [LLM Powered Autonomous Agents (Lilian Weng)](https://lilianweng.github.io/posts/2023-06-23-agent/)
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course)
- [Model Context Protocol](https://modelcontextprotocol.io/)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)
- [LangGraph](https://langchain-ai.github.io/langgraph/)

## Agent memory

- [Memory tool (Claude docs)](https://platform.claude.com/docs/en/agents-and-tools/tool-use/memory-tool)
- [Memory and context management cookbook (Claude)](https://platform.claude.com/cookbook/tool-use-memory-cookbook)
- [Mem0: memory layer for AI agents](https://github.com/mem0ai/mem0)
- [Letta (formerly MemGPT): stateful agents with long-term memory](https://github.com/letta-ai/letta)
- [Graphiti (Zep): temporal knowledge graphs for agent memory](https://github.com/getzep/graphiti)
- [LangMem: long-term memory for LangGraph agents](https://github.com/langchain-ai/langmem)
- [A-MEM: Zettelkasten-style agentic memory](https://github.com/agiresearch/A-mem)
- [Agent Memory Paper List](https://github.com/Shichun-Liu/Agent-Memory-Paper-List)
- [State of AI Agent Memory 2026 (Mem0 blog)](https://mem0.ai/blog/state-of-ai-agent-memory-2026)
- [Best AI Agent Memory Frameworks in 2026 (Atlan)](https://atlan.com/know/best-ai-agent-memory-frameworks-2026/)

## Agent sandboxes

### Isolation runtimes

- [Firecracker: microVMs](https://github.com/firecracker-microvm/firecracker)
- [gVisor: userspace kernel](https://github.com/google/gvisor)
- [Kata Containers: containers in lightweight VMs](https://github.com/kata-containers/kata-containers)
- [E2B: open source sandboxes for AI agents](https://github.com/e2b-dev/E2B)
- [sandbox-runtime (Anthropic): local sandbox for coding agents](https://github.com/anthropic-experimental/sandbox-runtime)

### Build and hands-on

- [agent-sandbox (kubernetes-sigs)](https://github.com/kubernetes-sigs/agent-sandbox)
- [agent-sandbox docs](https://agent-sandbox.sigs.k8s.io/)
- [cased-sandboxes: one Python interface over E2B, Modal, Daytona, Vercel and Sprites](https://pypi.org/project/cased-sandboxes/)
- [AgentCoreSandbox integration (LangChain)](https://docs.langchain.com/oss/python/integrations/sandboxes/aws)
- [Build research agents with Deep Agents and Bedrock AgentCore (AWS)](https://aws.amazon.com/blogs/machine-learning/build-context-rich-research-agents-with-deep-agents-and-bedrock-agentcore/)
- [AgentCoreRuntimeSandbox reference (Mastra)](https://mastra.ai/reference/workspace/agentcore-runtime-sandbox)

### Concepts and comparisons

- [Agent Sandboxing (Agentic AI Knowledge Base)](https://agentic-ai.readthedocs.io/en/latest/SecurityFrameworks/agent-sandboxing/)
- [How to sandbox AI agents: microVMs, gVisor and isolation (Northflank)](https://northflank.com/blog/how-to-sandbox-ai-agents)
- [AI agent sandbox guide (Firecrawl)](https://www.firecrawl.dev/blog/ai-agent-sandbox)
- [AI agent sandboxing guide: primitives, runtimes and platforms (Manveer C.)](https://manveerc.substack.com/p/ai-agent-sandboxing-guide)
- [Self-hosting Firecracker and E2B with GPUs (Spheron)](https://www.spheron.network/blog/ai-agent-code-execution-sandbox-e2b-daytona-firecracker/)
- [AI agent sandbox providers compared 2026 (Upstash)](https://upstash.com/blog/ai-agent-sandbox-providers-compared-2026)

### Security and incidents

- [Anatomy of a Frontier Lab Agent Intrusion (Hugging Face)](https://huggingface.co/blog/agent-intrusion-technical-timeline)
- [OpenAI agent used exposed credentials (The Hacker News)](https://thehackernews.com/2026/07/openai-agent-used-exposed-credentials.html)
- [OpenAI's agent escaped its sandbox during a security test (Malwarebytes)](https://www.malwarebytes.com/blog/news/2026/07/openais-agent-escaped-its-sandbox-during-a-security-test)

## AI for SRE and DevOps

- [HolmesGPT: SRE agent (CNCF Sandbox)](https://github.com/HolmesGPT/holmesgpt)
- [Awesome SRE Agents](https://github.com/last9/awesome-sre-agents)
- [k8sgpt: scan and explain Kubernetes issues with LLMs](https://github.com/k8sgpt-ai/k8sgpt)
- [kagent: cloud native agentic AI on Kubernetes](https://github.com/kagent-dev/kagent)
- [HolmesGPT docs](https://holmesgpt.dev/)
- [K8sGPT docs](https://docs.k8sgpt.ai/)
- [kagent docs](https://kagent.dev/docs/kagent/)
- [kubernetes-mcp-server: MCP server for Kubernetes, with evals and a read-only ServiceAccount guide](https://github.com/containers/kubernetes-mcp-server)

## Agent security and prompt injection

- [Prompt injection series (Simon Willison)](https://simonwillison.net/series/prompt-injection/)
- [Design Patterns for Securing LLM Agents against Prompt Injections (Simon Willison)](https://simonwillison.net/2025/Jun/13/prompt-injection-design-patterns/)
- [CaMeL: a DeepMind approach to prompt injection (Simon Willison)](https://simonwillison.net/2025/Apr/11/camel/)
- [Agents Rule of Two and The Attacker Moves Second (Simon Willison)](https://simonwillison.net/2025/Nov/2/new-prompt-injection-papers/)

## RAG and LLM apps in production

- [LlamaIndex docs](https://docs.llamaindex.ai/)
- [Building LLM applications for production (Chip Huyen)](https://huyenchip.com/2023/04/11/llm-engineering.html)
- [Patterns for Building LLM-based Systems & Products (Eugene Yan)](https://eugeneyan.com/writing/llm-patterns/)
- [Your AI Product Needs Evals (Hamel Husain)](https://hamel.dev/blog/posts/evals/)

## Inference and serving

### Engines

- [vLLM](https://docs.vllm.ai/)
- [vllm-metal: vLLM plugin for Apple Silicon](https://github.com/vllm-project/vllm-metal)
- [SGLang](https://github.com/sgl-project/sglang)
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)
- [LMDeploy](https://github.com/InternLM/lmdeploy)
- [Triton Inference Server](https://github.com/triton-inference-server/server)
- [FlashAttention](https://github.com/Dao-AILab/flash-attention)
- [LLM Compressor: quantize models for vLLM](https://github.com/vllm-project/llm-compressor)

### Local

- [Ollama](https://ollama.com/)
- [llama.cpp](https://github.com/ggml-org/llama.cpp)
- [MLX: array framework for Apple silicon](https://github.com/ml-explore/mlx)
- [mlx-lm: run LLMs with MLX](https://github.com/ml-explore/mlx-lm)

### Distributed and Kubernetes

- [llm-d: distributed inference on Kubernetes](https://llm-d.ai/)
- [NVIDIA Dynamo: datacenter scale distributed inference](https://github.com/ai-dynamo/dynamo)
- [vLLM production-stack](https://github.com/vllm-project/production-stack)
- [AIBrix: GenAI inference infrastructure](https://github.com/vllm-project/aibrix)
- [KubeAI: AI inference operator](https://github.com/kubeai-project/kubeai)
- [LeaderWorkerSet (LWS): multi-host pod groups](https://github.com/kubernetes-sigs/lws)
- [Gateway API Inference Extension](https://github.com/kubernetes-sigs/gateway-api-inference-extension)
- [LMCache: KV cache layer](https://github.com/LMCache/LMCache)
- [SkyPilot: run AI workloads on any cloud or cluster](https://github.com/skypilot-org/skypilot)

### Gateways

- [LiteLLM: AI gateway for 100+ LLM APIs](https://github.com/BerriAI/litellm)

## Forward Deployed Engineer (FDE)

- [FDE Analysis 2026: skills map from 276 job postings (OwlHub)](https://www.owlhub.dev/articles/fde-2026)
- [Forward Deployed Engineer (FDE) Roadmap (codebasics)](https://www.youtube.com/watch?v=uE4HTkDtp48)
- [Complete End To End AI FDE Project Implementation (Krish Naik)](https://www.youtube.com/watch?v=FSZhPDzESPU)
- [5 Projects That Will Actually Get You Hired In 2026 (Aishwarya Srinivasan)](https://www.youtube.com/watch?v=Fruw822BMBc)

## Videos

- [This New AI Model Could Change How We Build AI (Harkirat Singh)](https://www.youtube.com/watch?v=_aw32rFL680)

## Papers

- See [papers.md](papers.md)
