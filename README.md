# Cloud Experiments Lab

This repository is a **personal lab notebook for cloud, infrastructure, and AI experimentation**.

Instead of learning only through documentation or courses, systems are explored through **real deployments and observation of behaviour**.

The philosophy of this repository is simple:

experiment → observe → understand → record insight → iterate

Each experiment is intentionally small and focused. Over time, these experiments build a **practical knowledge base of real systems**.

---

# Why This Repo Exists

When experimenting frequently, knowledge can easily be lost:

experiment → understand → move on

This repository adds a lightweight **knowledge capture layer**:

experiment → insight → searchable knowledge → future reuse

The goal is **learning through experimentation while preserving insights**.

---

# Repository Structure

cloud-experiments
│
├─ README.md
├─ experiment-template.md
│
├─ experiments/
│ ├─ YYYY-MM-topic/
│ │ ├─ notes.md
│ │ ├─ terraform/
│ │ ├─ screenshots/
│ │ └─ logs/
│
├─ concepts/
│ ├─ api-gateways.md
│ └─ terraform-modules.md
│
└─ tools/
├─ terraform.md
├─ azure-cli.md
└─ ai-workflow.md



---

# Experiments

The **experiments folder** contains hands-on deployments and prototypes.

Examples of experiments may include:

- Azure APIM deployments
- Terraform module testing
- AWS infrastructure experiments
- API gateway architecture tests
- AI workflow automation
- AI agent prototypes
- RAG system experiments

Each experiment contains a **notes.md** file capturing what was attempted and what was learned.

---

# Experiment Template

Each experiment should follow a lightweight structure:

Goal  
Setup  
Actions  
Observations  
Key Insight  
Next Experiments  

Documentation should be **minimal but useful**.

Example:

Goal  
Understand Azure API Management and Terraform AVM modules.

Actions  
Deploy APIM using Terraform.

Observations  
APIM functions as an API gateway layer.

Key Insight  
AVM modules simplify infrastructure deployment significantly.

Next Experiment  
Test authentication policies.

---

# Workflow

Typical workflow for experiments:

Idea  
↓  
AI generates Terraform / code  
↓  
Deploy in Azure / AWS  
↓  
Observe behaviour  
↓  
Record insights  
↓  
Iterate  

Most experiments follow a terminal-driven workflow using:

- WSL Linux
- Terraform
- Azure CLI
- Git
- AI assistants (ChatGPT / Claude)

AI tools are used to accelerate:

- architecture design
- code generation
- debugging
- deployment iteration

---

# Documentation Philosophy

Documentation should **never block experimentation**.

Only capture the essentials:

- what was attempted
- what happened
- what was learned
- what to try next

Even **5 lines of notes is enough** to preserve valuable insights.

---

# Concepts

The **concepts folder** contains distilled understanding derived from experiments.

Examples:

- API gateways
- Terraform module patterns
- infrastructure architecture patterns
- cloud service roles

Concepts should be refined over time as experiments accumulate.

---

# Tools

The **tools folder** contains operational notes and quick references for tools frequently used during experiments.

Examples include:

- Terraform CLI usage
- Azure CLI commands
- AI-assisted development workflows

These are not full guides, but quick operational notes gathered during experimentation.

---

# Long-Term Goal

Over time this repository should evolve into a **personal architecture knowledge base**.

Experiments accumulate and eventually form patterns across areas such as:

- API gateways
- infrastructure as code
- authentication systems
- AI architectures
- distributed systems

The result is **practical understanding of real systems rather than purely theoretical knowledge**.

---

# Example Experiment

Example experiment structure:

experiments/2026-03-apim-avm

This experiment deploys Azure API Management using Terraform and Azure Verified Modules.

---

# Author

Personal experimentation environment for cloud systems, infrastructure, and AI-assisted development.



git add README.md
git commit -m "docs: add repo overview and experiment workflow"
git push



