# The Calibrated Mind

**AI strategy for the humans who have to make it work.**

---

## Who I Am

I'm Shaundra Ray, MBA, ARM, AIDA — and I've spent my career at the convergence point of the entire insurance enterprise.

My title is Senior Catastrophic Claims Adjuster. But the file tells a different story. Every catastrophic claim I've worked is a cross-functional audit of the carrier itself — touching underwriting integrity, actuarial accuracy, fraud exposure, safety services, compliance obligations, litigation risk, and reserving strategy, simultaneously. Policyholders hiding payroll. Fatalities with incomplete incident documentation. Reserve positions that have to hold up to regulatory scrutiny and actuarial review. Treatment trajectories that determine whether a carrier's loss ratio moves.

Most insurance professionals see the enterprise from one function. Adjusters see it from every file.

That vantage point is why I built this portfolio. AI adoption in insurance isn't a technology problem — it's an enterprise strategy problem. Getting it right requires understanding how decisions made in one function create risk or opportunity in another. I've been living that reality for over a decade.

I'm formally designated as an AI Champion at the largest workers' compensation carrier in Texas, where I'm actively evaluating and piloting enterprise AI tools across the organization. I built these frameworks because the ones I needed didn't exist — frameworks that account for the full complexity of a regulated carrier, not just one department's workflow.

This repository is the technical home of [The Calibrated Mind](https://substack.com/thecalibratedmind) — my newsletter and methodology for human-centered AI adoption in regulated insurance environments. If you want the deeper thinking behind any of these projects, that's where to find it.

---

## The Framework Behind This Portfolio

Most AI adoption in insurance fails for one reason: sequencing.

Carriers try to skip to the compelling parts — predictive analytics, automated decisions, generative outputs — before they've built the foundation those capabilities require. In a regulated environment, that's not just inefficient. It exposes the organization to governance risk it isn't equipped to manage.

The frameworks in this portfolio are built around a four-layer adoption pyramid. Each layer is sequenced by regulatory complexity and organizational readiness. Each one enables the next. And critically — each layer touches every function in the carrier, not just the one that feels the most immediate pain.

---

### Layer 1 — Document Intelligence

*This is where enterprise AI adoption starts in insurance. Full stop.*

Insurance carriers run on unstructured documents. Medical records, legal filings, policy applications, loss runs, IME reports, pharmacy records, treatment plans, employer injury reports, audit findings. These documents drive decisions across every function — claims, underwriting, compliance, actuarial, risk management. Until that document layer is structured, searchable, and intelligently processed, every AI initiative built on top of it is working on an unstable foundation.

Document intelligence is also the lowest-risk AI application available to a carrier. No autonomous decisions. No regulatory exposure. Humans remain fully in control. It is the right place to start — and most carriers aren't starting there because the payoff isn't as visible as the layers above it. That's a costly mistake.

**Projects in this layer:** [01 — Intelligent Document Ingestion](#project-01--intelligent-document-ingestion)

---

### Layer 2 — Decision Support

*AI surfaces the signal. The human makes the call.*

With a structured document foundation in place, AI can begin to support the decisions those documents inform — across every function that relies on them. Claims triage and complexity scoring. Underwriting risk flags. Reserve adequacy indicators. Litigation exposure signals. Compliance exception detection. Treatment trajectory analysis.

The design principle at this layer is non-negotiable: the human makes every final determination. AI is a thinking partner. The frameworks built here reflect what it actually takes to design decision support that practitioners trust — not just tools that surface output and hope someone acts on it.

**Projects in this layer:** [03 — AI Claims Triage](#project-03--ai-claims-triage-framework) · [04 — Adjuster AI Decision Support](#project-04--adjuster-ai-decision-support)

---

### Layer 3 — Predictive & Analytical

*Pattern recognition at scale — with governance built in.*

With clean document intelligence and proven decision support frameworks in place, carriers can begin using AI for predictive work: fraud signal detection, outcome modeling, portfolio analytics, exposure forecasting, loss development analysis. This is where the analytical value proposition becomes compelling to the C-suite. It's also where the governance requirements become most demanding.

Layer 3 only works if Layers 1 and 2 are solid. Skipping the foundation to reach this layer faster is how carriers end up with models they can't explain to a regulator — or worse, models making recommendations the organization doesn't have the infrastructure to validate.

**Projects in this layer:** Forthcoming

---

### Layer 4 — Autonomous & Generative

*Future state. Not yet. Build toward it deliberately.*

AI-assisted determinations, automated communications, generative underwriting support, dynamic policy language. This layer represents the frontier of what's possible in insurance AI — and it requires everything below it to be proven first. Carriers that rush to Layer 4 without the infrastructure to support it are taking on risk they cannot yet see or quantify.

**Projects in this layer:** Forthcoming

---

### The Adoption Pyramid at a Glance

| Layer | Name | Carrier Functions Affected | AI Role | Human Role | Regulatory Risk |
|-------|------|---------------------------|---------|------------|-----------------|
| 1 | Document Intelligence | Claims, Underwriting, Compliance, Actuarial | Ingests, extracts, summarizes | Reviews, validates, acts | Lowest |
| 2 | Decision Support | Claims, Underwriting, Risk Management, Legal | Surfaces signals and recommendations | Makes every final determination | Moderate |
| 3 | Predictive & Analytical | Actuarial, Finance, Fraud, Portfolio Mgmt | Detects patterns, models outcomes | Governs, interprets, challenges | Higher |
| 4 | Autonomous & Generative | Enterprise-wide | Drafts, determines, generates | Oversight and exception handling | Highest |

---

## The Projects

### Project 01 — Intelligent Document Ingestion

**An AI Foundation Framework for Insurance Carriers**

The strategic case for document intelligence as the foundational first layer of AI adoption across a carrier's operations. This project explains why it's the right starting point for the enterprise — not just claims — what good looks like operationally, and how to govern it responsibly. Includes a synthetic end-to-end workflow and tool evaluation criteria specific to the regulated insurance environment.

→ [View Project 01](./01-document-intelligence/README.md)

---

### Project 02 — Enterprise AI Tool Evaluation

**A Practitioner's Comparative Framework for Insurance Operations**

A structured, criteria-based framework for evaluating enterprise AI tools across insurance operations. Generic procurement criteria miss what matters in a regulated carrier environment: compliance posture, human override capability, audit trail quality, data residency, and domain-specific performance on insurance documents. This framework gives procurement and operations leaders the criteria that actually matter.

→ [View Project 02](./02-tool-evaluation/README.md)

---

### Project 03 — AI Claims Triage Framework

**Complexity Scoring and Routing for Workers' Compensation**

A structured framework for using AI to score, prioritize, and route incoming claims based on complexity, injury severity, litigation risk, and medical trajectory. Inconsistent triage creates downstream problems across reserving, actuarial, and legal — not just claims. This framework standardizes the initial assessment while keeping the adjuster in the decision seat.

→ [View Project 03](./03-claims-triage/README.md)

---

### Project 04 — Adjuster AI Decision Support

**Prompt Library and Integration Protocol for Catastrophic Claims**

A curated, tested library of AI prompts built specifically for catastrophic claims adjusters — by someone who has worked those files. The adjuster is where underwriting integrity, fraud exposure, actuarial accuracy, and compliance obligation converge. Getting AI integration right at this level matters to the entire carrier. This project addresses that directly.

→ [View Project 04](./04-adjuster-decision-support/README.md)

---

### Project 05 — The Calibrated Mind Methodology

**AI Adoption Framework for Insurance Operations**

The capstone. A complete, documented framework for human-centered AI adoption in regulated insurance environments — built for enterprise application, not departmental pilots. Includes an adoption readiness self-assessment and a change management guide focused on keeping people effective as AI is introduced. This is the piece that belongs in an executive conversation.

→ [View Project 05](./05-calibrated-mind-methodology/README.md)

---

## A Note on IP and Data

Every framework and artifact in this repository was built from industry knowledge, publicly available data, and first-principles reasoning. All examples and workflow illustrations use synthetic, entirely fictional data. No proprietary carrier materials, internal systems, real claim details, or vendor-specific evaluation findings appear anywhere in this portfolio.

Sources used throughout: TWCC published guidelines, NCCI industry statistics, publicly available workers' comp case law, and the author's own expertise and professional judgment.

---

## Let's Connect

If this work is relevant to what you're building — whether you're a carrier evaluating AI strategy, an executive thinking through enterprise adoption, or a recruiter looking for someone who can lead this work from the inside — I'd like to hear from you.

- **Newsletter:** [The Calibrated Mind on Substack](https://substack.com/thecalibratedmind) — deeper thinking on AI adoption in insurance, every Wednesday
- **LinkedIn:** [Shaundra Ray](https://linkedin.com/in/shaundraray) — frameworks, breakdowns, and practitioner takes on AI in insurance
- **GitHub:** You're already here.

---

*The Calibrated Mind · AI strategy for the humans who have to make it work.*
