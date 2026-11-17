<h1 align="center">Dhruv Sharma</h1>

<p align="center">
  Computer Science @ UT Dallas | AI Agents, ML & Software Engineering
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dhruv-sharma182">LinkedIn</a> &nbsp;|&nbsp;
  <a href="https://github.com/DhruvDS2">GitHub</a> &nbsp;|&nbsp;
  <a href="mailto:tosharmadhruv@gmail.com">Email</a>
</p>

---

## About

I'm a Computer Science student at the University of Texas at Dallas. I build AI agents, eval harnesses, and the backend systems around them, with a focus on making agents that actually finish real work.

I've built agent harnesses that fix bugs on their own, document pipelines that turn messy faxes into structured orders, and research code for LLM memory and matrix approximation. I like the parts around the model: evals, guardrails, data, and the plumbing that makes a system dependable.

## Experience

**Software Engineering Intern — Koyal AI (YC F25)**  
Built a self-improving agent harness that takes bug reports from Slack and Jira through to automated fixes with Claude Code or Codex. Added a gate that makes the agent reproduce a bug before fixing it; sub-agents reproduced bugs faithfully 80% of the time. Also benchmarked LoRA adapters and generative models for an image style-transfer pipeline.

**Undergraduate Researcher — University of Texas at Dallas (with Prof. Rishabh Iyer)**  
Researching in-context memory for LLMs: optimizing context, summarizing chat history, and condensing knowledge bases into the context window.

**Undergraduate Researcher — University of Texas at Dallas (CUR Decomposition)**  
Developed a deterministic CUR algorithm that runs 15% faster than full SVD and tightened additive spectral-norm error bounds by about 25%.

**Engineering Intern — Resolution Industry Trust Company**  
Documented 15 API endpoints as interactive, testable Mintlify docs and wrote engineering design docs used by engineers and product managers.

## Selected Projects

### [Faxtract](https://github.com/DhruvDS2/faxtract)
Agentic pipeline that turns degraded faxed radiology referrals into validated, insurance-verified imaging orders.
- 95.7% field accuracy on a 60-document ground-truth set at about $0.015 per referral.
- Cuts handling time from about 20 minutes to 20 seconds.
- Hand-built X12 270/271 eligibility, HL7 v2.5.1 order messages, and MLLP framing against a mock hospital system.
- Python, TypeScript, FastAPI, Postgres/pgvector, Claude vision, MCP. All synthetic data, no PHI.

### [Kindling](https://github.com/DhruvDS2/kindling)
Account-signal engine for a product-led K-12 company: tells sales which free schools are ready to buy and flags paying schools at risk of churning.
- Product-qualified-lead score reaches 73% precision vs. 37% for a naive baseline on a simulated school year with hidden outcomes.
- Counts school days instead of calendar days so breaks don't look like churn.
- Python, DuckDB, FastAPI, n8n, Slack, Streamlit.

### [PhoneGym](https://github.com/DhruvDS2/phonegym)
Simulated phone environment and eval harness for testing how well AI agents complete tasks on mobile. Built to work with any agent, not just one provider.

### PulseForge
CI gate that catches performance regressions by replaying sanitized production traffic against baseline and candidate builds.
- Deny-by-default secret sanitizer hardened with property-based tests.
- Content-addressed artifact store that maps directly onto S3.
- Capture middleware on FastAPI at about 0.16 ms overhead.

### [gsplat](https://github.com/DhruvDS2/gsplat)
CPU-only C++ renderer for pretrained 3D Gaussian Splatting scenes (Computer Graphics final project).

## Technical Stack

**Languages:** Python, TypeScript/JavaScript, C++, SQL

**AI & ML:** Claude API, MCP, Claude Code, Codex, RAG, pgvector, LangGraph, LoRA, NumPy, scikit-learn, LLM Evaluation

**Backend & Web:** FastAPI, Pydantic, React, Vite, REST APIs

**Data & Infrastructure:** PostgreSQL, DuckDB, AWS, n8n, Git, CI/CD, pytest

**Healthcare Protocols:** HL7 v2, X12 EDI, MLLP

## What I Like Building

- AI agents that reliably complete real-world workflows
- Eval harnesses and simulated environments that show how well agents actually perform
- Data pipelines that turn messy inputs into clean, structured output
- Backend systems that are simple, fast, and easy to trust

## Education

**University of Texas at Dallas**  
B.S. Computer Science, May 2027  
GPA: 3.83/4.00
