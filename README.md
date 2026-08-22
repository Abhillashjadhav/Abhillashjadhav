# Abhillash Jadhav

**AI product leader building governed engineering systems, reliable agentic workflows, and evaluation infrastructure.**

My work focuses on the difficult step between an impressive AI demo and a product that people can trust, adopt, operate, and improve. My background spans Amazon, Wayfair, and Cimpress, with hands-on product fluency across agentic workflows, RAG, multimodal AI, model routing, evaluation systems, observability, privacy, and human-in-the-loop design.

## Key products

| Product | Use it when you need to… | What it achieves |
| --- | --- | --- |
| **[PM Evals](https://github.com/Abhillashjadhav/pm-evals)** | Define observable quality for an AI feature, calibrate a judge against human goldens, and make a trace-backed release decision | Turns traces plus a plain-English rubric into criterion pass rates, worst traces, failure clusters, judge-calibration evidence, and a product-review-ready report through a deterministic local CLI |
| **[AI PM Skills Marketplace](https://github.com/Abhillashjadhav/AI-PM-essential-skills)** | Install one focused AI-product capability in Claude Code without adopting a monolithic PM system | Ships seven installable plugins for verification, tactical PM work, guarded loops, agent graphs, MCP migration, human writing, and AI-feature kill criteria; each produces a concrete artifact with validation fixtures |
| **[Loop Engineering + Graph Engineering](https://github.com/Abhillashjadhav/loop-engineering)** | Run one long-lived autonomous goal reliably, or coordinate several independently verifiable loops or workers that must branch and converge | Loop Engineering locks goals, executes atomic tasks, verifies evidence independently, detects drift, resumes safely, and recovers within explicit limits. The shipped Graph Engineering extension adds explicit topology, typed handoffs, permissions, budgets, conditional routing, deterministic joins, failure routing, and accountable approval gates |
| **[PM Agent OS](https://github.com/Abhillashjadhav/PM-agent-OS)** | Work through an AI product decision across discovery, strategy, build, launch, or iteration while keeping evidence, assumptions, trade-offs, and decision ownership explicit | Routes work through a `/pm` orchestrator, 40 lifecycle skills, and seven reviewer perspectives to produce reviewable product-decision artifacts instead of unchecked prompt output |
| **[Production Engineering OS](https://github.com/Abhillashjadhav/production-engineering-os)** | Turn an approved product decision into governed engineering work, reusable execution workflows, and independently verifiable completion evidence | Provides digest-locked contract intake, deterministic quality/security/trajectory gates, independent review, 21 verified workflow packs, guided approval controls, runtime assurance, and a one-command full-product path that ends in a verified local-process deployment and evidence manifest without silently merging or claiming cloud production deployment |

### Loop Engineering already extends to Graph Engineering

Loop Engineering makes one autonomous unit reliable. Graph Engineering carries the same reliability discipline into workflows where several specialist loops or workers must operate independently, exchange typed state, follow explicit permissions and budgets, and satisfy a deterministic join before the work can move forward.

Use one loop for one locked objective and one durable working context. Use a graph when independently verifiable branches need separate failure paths and an explicit convergence rule. A graph does not replace the loop: each graph node can itself be a guarded loop.

The shipped [`agent-graph-designer`](https://github.com/Abhillashjadhav/AI-PM-essential-skills/tree/main/agent-graph-designer) extension qualifies `LOOP_SUFFICIENT` versus `GRAPH_REQUIRED` and produces a machine-readable graph contract, synchronized topology, vendor-neutral runner skeleton, bounded recovery rules, and a named human approval boundary.

> **Keep the loop; engineer the graph around it.**

## Other working products

| Project | Use it when you need to… | What it achieves |
| --- | --- | --- |
| **[Dream Job Search Agent](https://github.com/Abhillashjadhav/Dreamjob-agent)** | Run a repeatable daily search for Director PM, Principal PM, and Group PM roles without rebuilding the workflow every morning | Runs an autonomous search/filter/score loop, creates tailored resumes for stronger fits plus ATS reports, gap analysis and interview-prep artifacts, writes a daily brief and trajectory evidence, and preserves the run in GitHub with Google Drive as a user-facing output path |
| **[LinkedIn Research Posts](https://github.com/Abhillashjadhav/Linkedin-research-posts)** | Turn research into credible LinkedIn drafts while keeping publishing under human control | Produces provenance-backed drafts, deterministic honesty checks, private review packages, and manual publishing handoffs |

## What I build for

- **Outcome before capability:** customer and business results matter more than model benchmarks.
- **Evaluation as product infrastructure:** final-answer accuracy is not enough; retrieval, tool use, trajectories, silent failures, safety, and consistency also matter.
- **Designed uncertainty:** clarification, abstention, escalation, fallback, monitoring, and rollback are product requirements.
- **Reusable leverage:** shared intelligence layers should accelerate teams without becoming central bottlenecks.
- **Explicit trade-offs:** quality, latency, cost, reliability, extensibility, adoption, and time-to-value must be managed deliberately.
- **Evidence before assertion:** public claims should map to working artifacts, reproducible checks, or clearly stated limitations.

## Problems I enjoy solving

- deciding which customer and business problems are worth solving with AI;
- separating reusable platform capabilities from product-specific workflows;
- choosing among prompting, RAG, tools, memory, routing, and fine-tuning;
- defining when an AI system should act, clarify, escalate, or stop;
- building evaluation systems that remain representative as products and models evolve;
- moving teams from fragile prototypes to reliable, measurable production products.

## Public-work boundary

These repositories are personal public artifacts. They do not reproduce employer systems or disclose proprietary metrics, internal architecture, customer information, or confidential implementation details. Each repository states its own validation scope and limitations.

If a project solves a real problem for you, use it, challenge it, open an issue, or star it so I know where to invest next.

## Connect

- **LinkedIn:** [linkedin.com/in/abhillashjadhav](https://www.linkedin.com/in/abhillashjadhav)
- **Topmate:** [topmate.io/abhillash_jadhav](https://topmate.io/abhillash_jadhav)
