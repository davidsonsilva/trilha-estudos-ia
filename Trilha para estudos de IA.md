# 🤖 Trilha de Estudos: Agentes de IA — Do Fundamento à Prática Real

> **Metodologia sugerida:** Dedique ~2h/dia. Cada módulo leva de 1 a 3 semanas. Pratique com projetos reais ao final de cada fase.

---

## 🟦 FASE 1 — Fundamentos (Módulos 01 a 03)

---

### 01 — Python
**Tópicos:** Sintaxe, OOP, Bibliotecas, Ambientes

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **Python for Everybody** (Coursera) | Curso | coursera.org/learn/python |
| **Automate the Boring Stuff with Python** (Al Sweigart) | 📚 Livro (grátis online) | automatetheboringstuff.com |
| **Fluent Python** (Luciano Ramalho) |  Livro avançado | O'Reilly |
| **Curso em Vídeo — Gustavo Guanabara** | 🎥 Vídeo (PT-BR) | youtube.com/cursoemvideo |
| **Documentação Oficial Python** | Docs | docs.python.org/3 |
| **Real Python** | Artigos/Tutoriais | realpython.com |

**Prática:** Crie scripts de automação, use `venv`/`conda`, pratique OOP com classes.

---

### 02 — Git & GitHub
**Tópicos:** Versionamento, Branches, GitHub Actions

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **Pro Git Book** (Scott Chacon) | 📚 Livro (grátis) | git-scm.com/book |
| **Git & GitHub para Iniciantes** — Willian Justen | 🎥 Vídeo (PT-BR) | youtube.com/WillianJusten |
| **GitHub Skills** (interativo) | Prática | skills.github.com |
| **GitHub Actions Documentation** | Docs | docs.github.com/actions |
| **Oh Shit, Git!?** | Referência rápida | ohshitgit.com |

**Prática:** Crie um repositório, faça branches, PRs e configure uma CI básica com GitHub Actions.

---

### 03 — APIs REST
**Tópicos:** HTTP/JSON, Autenticação, Consumo

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **REST API Tutorial** | Site | restapitutorial.com |
| **HTTP — MDN Web Docs** | Docs | developer.mozilla.org/HTTP |
| **FastAPI Official Docs** | Docs + Tutorial | fastapi.tiangolo.com |
| **Requests Library Docs** | Docs | requests.readthedocs.io |
| **Postman Learning Center** | Prática | learning.postman.com |
| **Curso de APIs REST** — Filipe Deschamps |  Vídeo (PT-BR) | youtube.com/filipedeschamps |

**Prática:** Consuma APIs públicas (OpenWeather, PokeAPI), crie uma API simples com FastAPI.

---

## 🟪 FASE 2 — IA Generativa (Módulos 04 a 05)

---

### 04 — LLMs & IA Generativa
**Tópicos:** Tokens, Embeddings, Context Window

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **Andrej Karpathy — Intro to LLMs** | 🎥 Vídeo | youtube.com/karpathy |
| **The Illustrated Transformer** (Jay Alammar) | Artigo | jalammar.github.io/illustrated-transformer |
| **Hugging Face Course** | Curso grátis | huggingface.co/learn |
| **OpenAI Documentation** | Docs | platform.openai.com/docs |
| **Anthropic Documentation** | Docs | docs.anthropic.com |
| **LLM University** (Cohere) | Curso | cohere.com/llmu |
| **Attention Is All You Need** (paper) | 📄 Paper | arxiv.org/abs/1706.03762 |

**Prática:** Use a API da OpenAI/Anthropic para gerar textos, explore embeddings com `text-embedding-3-small`.

---

### 05 — Engenharia de Prompt
**Tópicos:** Zero/Few-shot, Chain of Thought, Avaliação

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **OpenAI Prompt Engineering Guide** | Docs | platform.openai.com/docs/guides/prompt-engineering |
| **Anthropic Prompt Engineering Guide** | Docs | docs.anthropic.com/en/docs/build-with-claude/prompt-engineering |
| **Learn Prompting** (curso interativo) | Curso | learnprompting.org |
| **Prompt Engineering Guide** (DAIR.AI) | Site | promptengineeringguide.com |
| **Chip Huyen — Prompt Engineering** | Artigo | chiphuyen.com |
| **DeepLearning.AI — ChatGPT Prompt Engineering** | Curso grátis | deeplearning.ai/short-courses |

**Prática:** Crie prompts para diferentes tarefas, compare zero-shot vs few-shot, implemente Chain of Thought.

---

## 🟧 FASE 3 — Arquitetura de Agentes (Módulos 06 a 10)

---

### 06 — MCP (Model Context Protocol)
**Tópicos:** Tools, Resources, Prompts

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **MCP Official Specification** | Docs | modelcontextprotocol.io |
| **Anthropic MCP Introduction** | Docs | docs.anthropic.com/en/docs/agents-and-tools/mcp |
| **MCP GitHub Repository** | Código | github.com/modelcontextprotocol |
| **MCP Server Examples** | Código | github.com/modelcontextprotocol/servers |
| **Simon Willison — MCP Explained** | /Artigo | simonwillison.net |

**Prática:** Crie um servidor MCP simples que expõe uma ferramenta (ex: buscar clima).

---

### 07 — RAG (Retrieval-Augmented Generation)
**Tópicos:** Chunking, Indexação, Busca Semântica

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **RAG From Scratch** (LangChain) | Curso | youtube.com/langchain |
| **DeepLearning.AI — Building RAG Agents** | Curso grátis | deeplearning.ai/short-courses |
| **RAG Paper** (Lewis et al., 2020) | 📄 Paper | arxiv.org/abs/2005.11401 |
| **Pinecone — RAG Guide** | Artigo | pinecone.io/learn/retrieval-augmented-generation |
| **LlamaIndex Documentation** | Docs | docs.llamaindex.ai |

**Prática:** Construa um chatbot que responde perguntas sobre seus próprios documentos PDF.

---

### 08 — Bancos Vetoriais
**Tópicos:** Chroma, FAISS, Qdrant, Pinecone

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **ChromaDB Documentation** | Docs | docs.trychroma.com |
| **FAISS GitHub** | Código/Docs | github.com/facebookresearch/faiss |
| **Qdrant Documentation** | Docs | qdrant.tech/documentation |
| **Pinecone Documentation** | Docs | docs.pinecone.io |
| **Pinecone — Vector Databases Explained** | Artigo | pinecone.io/learn/vector-database |
| **FAISS Tutorial** (Hugging Face) | Tutorial | huggingface.co/blog/faiss |

**Prática:** Armazene embeddings de textos em ChromaDB e faça buscas semânticas.

---

### 09 — Frameworks para Agentes
**Tópicos:** LangChain, LangGraph, OpenAI Agents, CrewAI/LlamaIndex

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **LangChain Documentation** | Docs | python.langchain.com |
| **LangGraph Documentation** | Docs | langchain-ai.github.io/langgraph |
| **LangChain YouTube Channel** |  Vídeos | youtube.com/langchain |
| **CrewAI Documentation** | Docs | docs.crewai.com |
| **OpenAI Agents SDK** | Docs | openai.github.io/openai-agents-python |
| **LlamaIndex Documentation** | Docs | docs.llamaindex.ai |
| **DeepLearning.AI — AI Agents in LangGraph** | Curso grátis | deeplearning.ai/short-courses |

**Prática:** Crie um agente simples com LangChain que usa ferramentas (search, calculator).

---

### 10 — Construção de Agentes
**Tópicos:** Tool Calling, Memória, Multiagentes, Workflows

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **OpenAI Function Calling Docs** | Docs | platform.openai.com/docs/guides/function-calling |
| **Anthropic Tool Use Docs** | Docs | docs.anthropic.com/en/docs/build-with-claude/tool-use |
| **LangGraph — Multi-Agent Systems** | Tutorial | langchain-ai.github.io/langgraph |
| **CrewAI — Multi-Agent Collaboration** | Docs | docs.crewai.com |
| **AutoGen (Microsoft)** | Código/Docs | microsoft.github.io/autogen |
| **Deeplearning.AI — Multi AI Agent Systems with CrewAI** | Curso | deeplearning.ai/short-courses |

**Prática:** Construa um sistema multiagente onde um agente pesquisa e outro resume.

---

## 🟩 FASE 4 — Produção (Módulos 11 a 14)

---

### 11 — Observabilidade
**Tópicos:** Logs | Traces, Métricas, Custos por token, Avaliação

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **LangSmith Documentation** | Docs | docs.smith.langchain.com |
| **Arize Phoenix** | Docs | docs.arize.com/phoenix |
| **OpenTelemetry Documentation** | Docs | opentelemetry.io |
| **Langfuse** (open-source LLM observability) | Docs | langfuse.com |
| **Ragas — RAG Evaluation Framework** | Código | github.com/explodinggradients/ragas |
| **DeepLearning.AI — Evaluating AI Agents** | Curso | deeplearning.ai/short-courses |

**Prática:** Instrumente um agente com LangSmith ou Langfuse para rastrear chamadas e custos.

---

### 12 — Deploy & Infra
**Tópicos:** Docker, Kubernetes, CI/CD

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **Docker Documentation** | Docs | docs.docker.com |
| **Docker — Getting Started** | Tutorial | docs.docker.com/get-started |
| **Kubernetes Documentation** | Docs | kubernetes.io/docs |
| **GitHub Actions Documentation** | Docs | docs.github.com/actions |
| **Nana Janashia — Docker & Kubernetes** |  Vídeo | youtube.com/TechWorld-with-Nana |
| **FastAPI + Docker Deploy** | Tutorial | fastapi.tiangolo.com/deployment/docker |

**Prática:** Containerize uma aplicação FastAPI com Docker e faça deploy na Railway ou Render.

---

### 13 — Segurança
**Tópicos:** Privacidade, LGPD, Boas práticas

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **OWASP Top 10 for LLM Applications** | Docs | owasp.org/www-project-top-10-for-large-language-model-applications |
| **LGPD — Lei 13.709/2018** | Legislação | planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm |
| **Anthropic — Responsible Scaling Policy** | Docs | anthropic.com/responsible-scaling-policy |
| **NIST AI Risk Management Framework** | Docs | nist.gov/ai |
| **Google — Responsible AI Practices** | Docs | ai.google/responsibilities |

**Prática:** Implemente sanitização de inputs, masking de PII e rate limiting em um agente.

---

### 14 — Escalabilidade & Produção
**Tópicos:** Performance, Resiliência, Monitoramento

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **System Design Primer** | GitHub | github.com/donnemartin/system-design-primer |
| **Designing Data-Intensive Applications** (Martin Kleppmann) | 📚 Livro | O'Reilly |
| **Prometheus + Grafana Docs** | Docs | prometheus.io / grafana.com/docs |
| **AWS Well-Architected Framework** | Docs | aws.amazon.com/architecture/well-architected |
| **SRE Book** (Google) | 📚 Livro grátis | sre.google/books |

**Prática:** Adicione caching (Redis), retries com backoff e monitoramento com Prometheus ao seu agente.

---

## 🟥 FASE 5 — Carreira (Módulo 15)

---

### 15 — Portfólio & Comunidade

| Recurso | Tipo | Link / Referência |
|---|---|---|
| **GitHub Profile README Guide** | Tutorial | docs.github.com/account-and-profile |
| **Hugging Face Community** | Comunidade | huggingface.co |
| **LangChain Discord** | Comunidade | discord.gg/langchain |
| **r/LocalLLaMA** (Reddit) | Comunidade | reddit.com/r/LocalLLaMA |
| **Papers With Code** | Pesquisa | paperswithcode.com |
| **AI Engineering Podcast** | 🎙️ Podcast | aiengineeringpodcast.com |
| **The Batch** (Andrew Ng) | Newsletter | deeplearning.ai/the-batch |

**Prática:** Publique 3 projetos no GitHub com READMEs bem documentados. Escreva artigos no Medium/Dev.to.

---

##  Projetos que Fazem a Diferença

| # | Projeto | Tecnologias |
|---|---|---|
| 1 | **Chat com Documentos (RAG)** | LangChain + ChromaDB + OpenAI |
| 2 | **Agente de Atendimento** | CrewAI + Tool Calling + Memória |
| 3 | **Agente que consulta APIs externas** | Function Calling + FastAPI |
| 4 | **Agente para análise de logs** | LangChain + Pandas + LLM |
| 5 | **Sistema Multiagente** | LangGraph ou AutoGen |
| 6 | **Agente com MCP + Ferramentas** | MCP Server + Anthropic Claude |
| 7 | **Dashboards & Insights com IA** | Streamlit + LLM + Gráficos |

---

## 📅 Cronograma Sugerido (16 semanas)

| Semanas | Fase | Módulos |
|---|---|---|
| 1–3 | Fundamentos | 01, 02, 03 |
| 4–5 | IA Generativa | 04, 05 |
| 6–10 | Arquitetura de Agentes | 06, 07, 08, 09, 10 |
| 11–14 | Produção | 11, 12, 13, 14 |
| 15–16 | Portfólio | 15 + Projetos |

---

> 💡 **Dica de ouro:** Não tente aprender tudo de uma vez. Foque em **construir projetos reais** a cada módulo. O portfólio vale mais que certificados.

> 📌 **Frase da imagem:** *"A IA não substitui profissionais. Mas profissionais que usam IA substituem quem não usa."*