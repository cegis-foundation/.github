# CEGIS - GitHub Organisation

> **Centre for Effective Governance of Indian States (CEGIS)**
> This GitHub organisation is the single source of truth for all technical work across CEGIS - built and maintained by the CEGIS Tech Team, and open for contribution from analysts, domain experts, and external collaborators across teams.

---

## Why a centralised GitHub organisation?

Managing code across personal accounts or scattered repositories creates friction, knowledge silos, and security blind spots. By bringing all work under one GitHub organisation, CEGIS gets:

- **Discoverability** - any team member can find any project in one place, understand its purpose from a README, and contribute without chasing down repository links.
- **Auditability** - a full audit trail of who changed what, when, and why - critical for government-facing analytics work.
- **Secure secrets management** - API keys, database credentials, and SSH keys are stored as organisation-level secrets in GitHub, never in code.
- **Onboarding speed** - a new team member joins the organisation, gets added to the right team, and immediately has the correct access to every relevant repository - no manual repo-by-repo setup.
- **Knowledge retention** - code and context stay with the organisation, not with individuals, even when team members move on.
- **Reusability across teams** - dashboards, analytics scripts, and data utilities built for one project can be discovered and reused by any other team, avoiding duplicated effort.
- **Co-working by design** - contributors from different teams - tech, policy, research, or external partners - can collaborate on the same repository through branches and pull requests, with full visibility into each other's work.

---

## Repository & Contributer

**Naming convention:** all repositories use lowercase kebab-case. Project-specific repositories are prefixed with the project name (e.g. `cumta-data-pipelines`, `cumta-analytics`).
**What you can contribute:**
- Python scripts for data analysis, indicator computation, or statistical modelling
- Dashboard code - Streamlit apps, Plotly figures, or reusable chart components
- SQL queries and data transformation logic
- Documentation, methodology notes, or data dictionaries

---

## Getting started

**For all contributors (Tech Team and beyond):**

1. Request access via the `.github` repository → *New Issue* → *Access Request* - mention your team and what you want to contribute or view.
2. Once added, clone the relevant repository: `git clone git@github.com:cegis-org/<repo-name>.git`
3. Read the repository-level `README.md` for setup and contribution instructions specific to that project.
4. Create a branch for your work: `git checkout -b yourname/feature-description`
5. Open a pull request when ready - the Tech Team will review and merge.

**Want to contribute a dashboard or analytics script but unsure where to start?** Open an issue in the `analytics` or `shared-libs` repository describing what you want to add. The Tech Team will help scope it and set up the right structure.

---

## Contact

For organisation-level queries - access issues, new repository requests, billing - open an issue in the `.github` repository or contact the CEGIS engineering team.
