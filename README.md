[README.md](https://github.com/user-attachments/files/29227697/README.md)
# The Calibrated Mind

**AI strategy for the humans who have to make it work.**

---

## Who I Am

I'm Shaundra Ray, MBA, ARM, AIDA. I'm a Senior Catastrophic Claims Adjuster — and I've built a reputation for telling people what's actually happening, not what they want to hear.

That trait has served me well in claims. A catastrophic file doesn't lie. The medical records, the payroll audit, the incident report, the reserve history — it all tells a story. My job is to read it accurately and act on it honestly, even when the truth is inconvenient.

It turns out that's exactly the skill set AI adoption needs right now.

Here's what I've learned working the most complex files in workers' compensation: the adjuster is where the whole carrier converges. I've worked files where employers were hiding payroll. Where fatalities were underdocumented. Where reserves were a best guess dressed up as analysis. Where fraud signals were buried in a stack of medical records nobody had time to read. That's not just a claims story — that's underwriting integrity, actuarial accuracy, compliance exposure, and litigation risk all showing up on one desk at the same time.

So when carriers ask whether their AI strategy is working, I have a different vantage point than most. I've seen what happens downstream when the foundation isn't solid. I know which problems actually need solving and which ones just look urgent. And I'm not going to tell you your pilot is a success when the real work hasn't started yet.

I'm formally designated as an AI Champion at the largest workers' compensation carrier in Texas, where I'm actively evaluating enterprise AI tools and building the internal case for responsible adoption. I built these frameworks because the honest ones didn't exist yet — ones that account for how insurance actually works, not how it looks in a vendor demo.

This repository is the technical home of [The Calibrated Mind](https://thecalibratedmind.com) — my newsletter and methodology for human-centered AI adoption in regulated insurance environments. If you want the deeper thinking behind any of these projects, that's where to find it.

---

## The Framework Behind This Portfolio

Let me be direct about something: most AI adoption in insurance is out of sequence.

Carriers are chasing the compelling use cases — predictive analytics, automated decisions, generative outputs — before they've built the foundation those things require. I understand why. The foundation isn't glamorous. It doesn't make for a good board presentation. But skipping it doesn't make the risk disappear. It just moves it downstream where it's harder to see and more expensive to fix.

The frameworks in this portfolio are built around a four-layer adoption pyramid. The sequencing isn't arbitrary — it maps to regulatory complexity, organizational readiness, and where human judgment is non-negotiable. Every layer touches the full carrier. Every layer has to be earned before the next one is attempted.

---

### Layer 1 — Document Intelligence

*Start here. I mean it.*

Insurance carriers run on unstructured documents. Medical records, legal filings, policy applications, loss runs, IME reports, pharmacy records, audit findings. These documents drive decisions across every function — claims, underwriting, compliance, actuarial, risk management. Until that document layer is structured and intelligently processed, everything built above it is unstable.

Document intelligence is also the lowest-risk AI application a carrier can deploy. No autonomous decisions. No regulatory exposure. Humans stay in control. It is the right place to start — and most carriers aren't starting there because the ROI isn't as visible as the layers above it.

That's a mistake I can help you avoid.

**Projects in this layer:** [01 — Intelligent Document Ingestion](#project-01--intelligent-document-ingestion)

---

### Layer 2 — Decision Support

*AI brings the signal. You make the call.*

Once documents are structured, AI can start supporting the decisions those documents inform — across claims, underwriting, risk management, and legal. Triage scoring. Reserve flags. Litigation exposure indicators. Compliance exceptions. Treatment trajectory analysis.

The design principle here is non-negotiable: the human makes every final determination. AI is a thinking partner, not a decision-maker. And building decision support that practitioners actually trust — versus tools that surface output nobody acts on — requires knowing how those decisions get made in practice. That's what separates these frameworks from generic solutions.

**Projects in this layer:** [03 — AI Claims Triage](#project-03--ai-claims-triage-framework) · [04 — Adjuster AI Decision Support](#project-04--adjuster-ai-decision-support)

---

### Layer 3 — Predictive & Analytical

*Pattern recognition at scale — but only if the foundation holds.*

With clean document intelligence and proven decision support in place, carriers can begin using AI for predictive work: fraud signal detection, outcome modeling, portfolio analytics, exposure forecasting, loss development analysis. This is where the value proposition gets executives excited. It's also where governance requirements get serious.

I'll say it plainly: Layer 3 only works if Layers 1 and 2 are solid. Organizations that skip ahead end up with models they can't explain to a regulator and recommendations they can't validate. I've seen what that looks like from the file level. It's not a technology problem — it's a sequencing problem.

**Projects in this layer:** Forthcoming

---

### Layer 4 — Autonomous & Generative

*The frontier. Earn it.*

AI-assisted determinations, automated communications, generative underwriting support. This is where insurance AI is heading — and it requires everything below it to be proven first. Carriers rushing to Layer 4 without the infrastructure to support it are taking on risk they cannot yet see or quantify.

Build toward it deliberately. Don't let a vendor timeline set your adoption pace.

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

The strategic case for document intelligence as the foundational first layer of AI adoption across carrier operations. This project explains why it's the right starting point — not just for claims, but for the enterprise — what good looks like operationally, and how to govern it responsibly. Includes a synthetic end-to-end workflow and tool evaluation criteria built specifically for the regulated insurance environment.

→ [View Project 01](./01-document-intelligence/README.md)

---

### Project 02 — Enterprise AI Tool Evaluation

**A Practitioner's Comparative Framework for Insurance Operations**

A structured, criteria-based framework for evaluating enterprise AI tools across carrier operations. Generic procurement criteria miss what matters in a regulated environment: compliance posture, human override capability, audit trail quality, data residency, and real performance on insurance documents. This framework gives you the criteria that actually matter — before you've already signed the contract.

→ [View Project 02](./02-tool-evaluation/README.md)

---

### Project 03 — AI Claims Triage Framework

**Complexity Scoring and Routing for Workers' Compensation**

Inconsistent triage doesn't just create claims problems — it creates reserving problems, actuarial problems, and litigation problems. This framework uses AI to score, prioritize, and route incoming claims based on complexity, injury severity, litigation risk, and medical trajectory. It standardizes the assessment without removing the adjuster from the decision.

→ [View Project 03](./03-claims-triage/README.md)

---

### Project 04 — Adjuster AI Decision Support

**Prompt Library and Integration Protocol for Catastrophic Claims**

The adjuster is where underwriting integrity, fraud exposure, actuarial accuracy, and compliance obligation all land at once. Getting AI integration right at this level matters to the entire carrier — not just the claims department. This is a curated, tested prompt library built by someone who has worked those files, paired with a protocol for integrating AI assistance without displacing the judgment that makes adjusters valuable.

→ [View Project 04](./04-adjuster-decision-support/README.md)

---

### Project 05 — The Calibrated Mind Methodology

**AI Adoption Framework for Insurance Operations**

The capstone. A complete framework for human-centered AI adoption in regulated insurance environments — built for enterprise application, not departmental pilots. Includes an adoption readiness self-assessment and a change management guide focused on keeping people effective as AI is introduced. This is the piece that belongs in an executive conversation — and it's written for one.

→ [View Project 05](./05-calibrated-mind-methodology/README.md)

---

## A Note on IP and Data

Every framework and artifact in this repository was built from industry knowledge, publicly available data, and first-principles reasoning. All examples and workflow illustrations use synthetic, entirely fictional data. No proprietary carrier materials, internal systems, real claim details, or vendor-specific evaluation findings appear anywhere in this portfolio.

Sources used throughout: TWCC published guidelines, NCCI industry statistics, publicly available workers' comp case law, and the author's own expertise and professional judgment.

---

## Let's Connect

If this work is relevant to what you're building — whether you're a carrier evaluating AI strategy, an executive who wants a straight answer about where your adoption actually stands, or a recruiter looking for someone who can lead this work from the inside — I'd like to hear from you.

- **Newsletter:** [The Calibrated Mind](https://thecalibratedmind.com) — deeper thinking on AI adoption in insurance, every Wednesday
- **LinkedIn:** [Shaundra Ray](https://www.linkedin.com/in/iamshaundra/) — frameworks, breakdowns, and practitioner takes on AI in insurance
- **GitHub:** You're already here.

---

*The Calibrated Mind · AI strategy for the humans who have to make it work.*
