# RESUME + CAREER HANDOFF DOCUMENT
# For AI agent continuity — contains full resume and context notes

---

# PART 1: RESUME (BASELINE — UNFORMATTED FOR AI READABILITY)

---

CANDIDATE: [Full Name]
LOCATION: [City, State]
CONTACT: [phone] | [email] | [LinkedIn URL] | [GitHub URL]

---

## EXPERIENCE

### Bank of America — Software Engineer II
July 2022 – Present

- Piloted and led adoption of Single Click Deploy (SCD), a release workflow built on XLR and Ansible that consolidated 7 manual deployment steps into 2 automated pipelines with a unified UI; 3 of 6 teams have adopted the workflow to date
- Leading cross-team adoption of an automated credential management system that eliminates approximately 45 story points of manual service ID password rotation work per cycle, covering 30 service IDs across 3 regions with plans to scale to all 6 teams
- Authored adoption and onboarding documentation for SCD, enabling engineering teams to independently integrate the new release tooling without additional support overhead
- Maintained and improved SDLC process documentation used by approximately 100 engineers across 3 regions
- Contributed to Project Helm, an AI-assisted vulnerability scanning initiative that surfaced 150 story points of remediation work across the organization; performed library version upgrades and removed obsolete dependencies with full test validation to prevent unintended regressions
- Mentored 4 incoming Technology Analyst Program graduates through onboarding and technical ramp-up
- Provided on-call production support for a distributed, message-oriented application integrated with 20 to 30 internal and external systems, including log tracing and root-cause debugging
- Contributed to the launch and ongoing moderation of an internal developer Q&A platform serving thousands of engineers across the organization

---

## PROJECTS

### Freshdesk AI Customer Service Assistant
Stack: Python, Claude API, MCP (Model Context Protocol), Freshdesk
Status: In Progress

- Building an MCP server integrating Freshdesk with Claude to automate ticket routing and customer response drafting for a live e-commerce business; sole engineer and solution owner

---

## LANGUAGES & TECHNOLOGIES

Languages: Python, Java, JavaScript, SQL, Bash
CI/CD & Release Automation: Jenkins, Ansible, XLR (XebiaLabs Release)
Monitoring & Observability: Splunk
Infrastructure: Linux, distributed messaging middleware
Version Control: Git, Bitbucket

---

## EDUCATION

University of Rochester — B.A., Computer Science
Graduation: 2022

---

# PART 2: HANDOFF DOCUMENTATION
# Everything a new AI agent needs to continue working on this resume intelligently

---

## CANDIDATE SNAPSHOT

- Name: [Full Name — not yet provided, placeholder in resume]
- Current employer: Bank of America
- Start date at BofA: July 2022
- Program entry: TAP (Technology Analyst Program) — BofA's new grad rotational program; completed after year one, transitioned to permanent Software Engineer II role on the same or related team
- Title clarification: Internal title is "Officer Software Engineer 2" — "Officer" is a BofA corporate band designation (Band 5), not a functional title. External-facing resume uses "Software Engineer II" only.
- GPA: 3.1 — omitted from resume (below threshold)
- Degree: B.A., Computer Science, University of Rochester, 2022

---

## CAREER CONTEXT & GOALS

### What the candidate is optimizing for:
- Better compensation
- More ownership and agency over work
- Openness to staying in fintech but actively interested in moving into broader tech (big tech, DevOps/SRE, AI-adjacent roles)

### Target role lanes (in priority order as understood):
1. Software Engineer at big tech or growth-stage tech company (primary baseline target)
2. DevOps / SRE / Release Engineering (strong fit given tooling experience)
3. AI Engineer (aspirational — credibly supported by MCP side project, but no ML/model training background)
4. Fintech SWE (open to it, not the primary goal)

### Lane recommendation made during session:
Build one strong SWE baseline resume with platform/tooling lean. Create two light variants:
- Variant A: DevOps/SRE — reorder bullets to lead with SCD and password vaulting, add 2-sentence summary emphasizing release engineering
- Variant B: AI Engineer — lead with MCP project and Project Helm, add summary emphasizing AI tooling integration experience

### What the candidate is moving away from:
- Pure finance/operations-adjacent work
- Roles with no ownership or initiative

---

## EMPLOYMENT HISTORY

### Bank of America (July 2022 – Present)
Only employer post-graduation. No prior internships mentioned.

Role structure:
- Year 1: TAP (Technology Analyst Program) — new grad rotational program
- Year 2+: Permanent Software Engineer II on the same team/org

Team context:
- Works on a distributed, message-oriented application
- Messaging middleware used (candidate unsure of exact technology — did not confirm IBM MQ, Kafka, etc. — do not assume)
- Application integrates with 20–30 internal and external systems
- Application is NOT cloud-hosted; no containers (Docker/Kubernetes) in current stack
- Team is organized across 3 regions; SDLC team total ~100 engineers

---

## PROJECT DETAILS

### 1. Single Click Deploy (SCD) — HIGHEST PRIORITY BULLET
- What it is: A new internal release workflow built on XLR (XebiaLabs Release) and Ansible
- Problem solved: Previously, a worst-case full release involved 7 distinct manual steps:
  config seed, DB upgrade, process shutdown, new process deploy, Autosys upgrade, server upgrade, UI upgrade
  (not all steps required every release, but server upgrade and UI upgrade always present)
- Solution: Consolidated into 2 automated pipelines with a cohesive UI
- Candidate's role: Piloted the workflow; leading adoption across the team
- Adoption status: 3 of 6 teams adopted to date
- Documentation: Candidate authored onboarding docs specifically to enable new teams to adopt SCD independently — this is NOT generic dev onboarding docs

### 2. Password Vaulting Project — STRONG OWNERSHIP STORY
- What it is: Adoption of an automated credential rotation system for service IDs
- Problem solved: Service IDs used for DB connections and service tasks required manual password rotation — painful, multi-team coordination effort every rotation cycle
- Candidate's role: Adoption lead / liaison — did NOT build the rotation/publishing mechanism (built by another team); responsible for integrating it into the ecosystem, coordinating all dependent teams, and ensuring production rollout
- Scale: 10 service IDs per region × 3 regions = 30 IDs total
- Quantified impact: ~1.5 SP per ID per rotation cycle (~4 months) = ~45 SP of manual work eliminated per cycle at full adoption
- Current status: 1 of 6 teams in test adoption; full rollout planned

### 3. Project Helm — AI ANGLE
- What it is: AI-assisted vulnerability scanning of the codebase
- Output: ~150 story points of remediation work surfaced and distributed across all teams
- Candidate's contribution: Participated in scanning phase and performed remediation work (library upgrades, removal of obsolete usages, regression testing)
- Note: Candidate did not do all 150 SP — did their share. Do not overstate sole ownership.
- Why it matters for resume: Positions candidate as having hands-on experience with AI tooling applied to engineering workflows — useful for AI Engineer targeting

### 4. Internal Developer Q&A Platform ("Internal Stack Overflow")
- What it is: An internal Q&A knowledge-sharing platform for engineers
- Candidate's role: Part of team that launched and moderated the platform
- Scale: Thousands of engineers across BofA use it
- Note: Candidate was a contributor/moderator, not the sole builder

### 5. MOC (Market on Close) Workflow — INTENTIONALLY OMITTED
- What it is: A guaranteed market-on-close order execution workflow for trading clients
- Why omitted: Candidate was a team contributor, not a pivotal component; lacks specific metrics or ownership angle; could not speak to it with confidence in an interview
- Decision: Leave out of resume. Can be revisited if candidate recalls more detail or finds a way to frame a specific contribution.

### 6. On-Call Production Support
- Distributed, message-oriented application
- 20–30 internal and external system integrations
- Responsibilities: log tracing, root-cause debugging, incident response
- Rotation frequency: not specified — do not assume

### 7. SDLC Documentation
- Candidate owns and continuously improves SDLC process documentation
- Scope: ~100 engineers across 3 regions depend on this documentation and the associated web server
- This is ongoing ownership work, not a one-time project

### 8. TAP Mentoring
- Mentored 4 incoming TAP (Technology Analyst Program) graduates after completing the program himself
- One year of program, then transitioned to permanent role

---

## SIDE PROJECT — MCP / FRESHDESK AI ASSISTANT

- Status: Work in progress — do NOT present as complete
- Stack: Python, Claude API, MCP (Model Context Protocol), Freshdesk
- Context: Built for a small e-commerce business (candidate's parents' business)
- Candidate's role: Sole engineer and solution owner — effectively functioning as a forward-deployed engineer
- Planned features: Ticket routing, customer response drafting
- Why it matters: This is real AI engineering work on a live system — not a tutorial or toy project. It meaningfully supports AI Engineer targeting and differentiates the candidate in that lane.
- Action for candidate: Prioritize completing ticket routing and response drafting features before applying to AI Engineer roles

---

## TECH STACK — VERIFIED HANDS-ON

Languages: Python, Java, JavaScript, SQL, Bash
CI/CD & Release: Jenkins, Ansible, XLR (XebiaLabs Release)
Monitoring: Splunk
Infrastructure: Linux
Messaging: Distributed messaging middleware (specific technology not confirmed)
Version Control: Git, Bitbucket
AI/API: Claude API, MCP (Model Context Protocol), Freshdesk API
Currently NOT hands-on with: Docker, Kubernetes, AWS, Azure, GCP, any ML frameworks

Tools intentionally omitted from resume: Jira (trivial tool per resume best practices)

---

## CERTIFICATIONS

None currently held.

Recommended pursuit order (as advised during session):
1. AWS Solutions Architect Associate — highest ROI, patches cloud gap directly
2. AWS DevOps Engineer Professional — if committing to DevOps/SRE lane
3. Terraform Associate (HashiCorp) — fast, valued in DevOps hiring, complements Ansible
4. CKA (Certified Kubernetes Administrator) — only if committing to DevOps lane

AI-specific certs: Not recommended yet — market immature, shipped projects outweigh certs in this space

---

## RESUME DECISIONS MADE (DO NOT REVERSE WITHOUT GOOD REASON)

- GPA (3.1) omitted — below threshold where it helps
- "Officer" title dropped — internal band designation, reads as compliance/risk externally
- TAP not listed as a separate role — it is a first-year program, not a distinct position
- MOC workflow omitted — thin ownership, no defensible metrics
- Splunk dashboard bullet removed — candidate unsure of outcome metrics
- Jira removed from tech stack — trivial tool
- Self-rated skill levels: none included
- No summary section — candidate has under 5 years experience and is not a career changer

---

## PLACEHOLDERS STILL OUTSTANDING

- Candidate's full name, phone, email, LinkedIn URL, GitHub URL
- Splunk dashboard outcome (removed from current draft — revisit if candidate recalls an actionable result)
- Messaging middleware technology name (IBM MQ, Kafka, RabbitMQ, etc.) — candidate was unsure; verify before adding to tech stack
- MCP project completion — ticket routing and response drafting; add metrics once live

---

## TONE & FRAMING PREFERENCES

- Candidate prefers factual, grounded bullets — does not want to overstate ownership or contribution
- Comfortable with quantified framing when numbers are defensible
- Wants to project ownership and initiative (not just "was part of team")
- No interest in AI cert padding — prefers shipped work as evidence

---

END OF DOCUMENT
