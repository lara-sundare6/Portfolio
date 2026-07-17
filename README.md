# Lara Sundare

AI infrastructure and AgentOps engineer. I turn messy platform problems into production systems: APIs, agents, governance tooling, and delivery infrastructure you can reuse.

**Chicago, IL** · [Blog](https://lara-sundare6.github.io/) · [Fly Island overview](https://lara-sundare6.github.io/fly-island/) · [LinkedIn](https://www.linkedin.com/in/lara-sundare6/) · [Email](mailto:larasundare@gmail.com)

---

## Start here (for hiring managers)

| What to open | Why |
|---|---|
| [Fly Island: AgentOps overview](https://lara-sundare6.github.io/fly-island/) | Solo-built AgentOps platform. Observe≠write agents, LLM safety gates, cost/carbon controls. Public proof page (core repo is proprietary). |
| [Biomimetic engineering essay](https://lara-sundare6.github.io/category/2026/07/10/biomimetic-engineering-capping-the-physical-cost-of-unbounded-ai.html) | Design thesis behind Fly Island. |
| [Blog](https://lara-sundare6.github.io/) | Writing and project notes. |
| [weather-crop-data-pipeline](https://github.com/lara-sundare6/weather-crop-data-pipeline) | Public data/pipeline work. |
| [cpd-gang-database-analysis](https://github.com/lara-sundare6/cpd-gang-database-analysis) | Ethics of data and algorithms research project. |

If you want a live architecture walkthrough of Fly Island, ask. Happy to screen-share in an interview.

---

## What I build now

- **Production AI systems** on Google Cloud: RAG pipelines, Cloud Run APIs, nightly ETL into vector stores, Terraform-managed secure enclaves.
- **AgentOps / reliability**: bounded remediation agents, structured model output, path allowlists, circuit breakers, shadow mode, token and carbon budgets.
- **Governance**: compliance scanning, SAIF-style scorecards, FERPA-aware landing zones, reusable delivery playbooks.
- **Developer experience**: GitHub Enterprise migrations, training, and CI/CD enablement from earlier consulting work.

Current role: Associate Cloud Consultant at Burwood Group (acquired by Sikich). Independent work: Fly Island.

---

## Fly Island

Solo-built AgentOps platform (Rust) for observing GitHub Actions failures, costing runs in USD and Software Carbon Intensity (SCI), and remediating only inside hard bounds.

- Persistent **Hoverfly** agents observe and plan. They have no write access.
- Ephemeral **Bee** agents execute one MCP write task and exit.
- Architecture tests keep reasoning code from importing write tools.
- Defaults to read/shadow mode until promotion criteria pass.

**Public overview:** https://lara-sundare6.github.io/fly-island/  
**Essay:** https://lara-sundare6.github.io/category/2026/07/10/biomimetic-engineering-capping-the-physical-cost-of-unbounded-ai.html

Earlier public experiments (`fly-island-v1`, `fly-island-v2`, `fly-islandv3`) are archived or superseded. The current product overview is the page above.

---

## Selected public projects

### CPD Gang Database Analysis
Ethics, bias, and community-impact analysis of algorithmic policing data.  
https://github.com/lara-sundare6/cpd-gang-database-analysis

### Weather / crop data pipeline
Public data pipeline work.  
https://github.com/lara-sundare6/weather-crop-data-pipeline

### GitHub Enterprise consulting (InfoMagnus, 2023–2024)
Fortune 500 migrations to GitHub Enterprise Cloud, training programs, and zero-install migration tooling with Azure VMs and GitHub Codespaces. Client names omitted here where appropriate.

---

## Stack (working set)

Rust (Tokio), Python, TypeScript, Terraform / OpenTofu, Google Cloud (Cloud Run, BigQuery, Workflows, GKE), Azure, GitHub Actions, Docker, Redis, OpenTelemetry, Prowler, LangChain / Vertex AI / Gemini Enterprise.

---

## Education

Graduate coursework in Computer Science, Illinois Institute of Technology (2021–2023).  
B.A., Audio Design and Production, Columbia College Chicago (2017–2019).

---

## Contact

- Email: larasundare@gmail.com
- LinkedIn: https://www.linkedin.com/in/lara-sundare6/
- Blog: https://lara-sundare6.github.io/
