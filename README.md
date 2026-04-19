# HomeRun — Co-living Mediator Dashboard

> *One Roof. One Dashboard.*

A human-computer interaction (HCI) design project exploring coordination friction in co-living environments, culminating in a fixed-position desktop dashboard system for shared household management.

---

## Project Overview

**HomeRun** is a conceptual desktop system designed to act as a neutral, centralised "Co-living Mediator" for residents in high-density shared housing. The system depersonalises household administration by shifting chore tracking, expense splitting, and social coordination away from personal messaging apps onto a shared, persistent dashboard.

This project was completed as part of **NM3243 (Interaction Design)** at the National University of Singapore.

---

## The Problem

Residents in co-living environments currently rely on a fragmented ecosystem of tools — WhatsApp for communication, Splitwise for bills, physical whiteboards for chores — none of which address the underlying emotional friction of shared living:

- Critical household information gets buried in high-volume group chats
- Reminders sent person-to-person feel like "nagging," creating interpersonal tension
- One person (the de facto "Organiser") carries a disproportionate cognitive load
- Subjective standards for cleanliness and contributions are never formally codified

---

## Design Process

````
Discovery → Requirements → Prototyping → User Testing → Iteration → Heuristic Evaluation
````

| Phase | Methods Used |
|---|---|
| Discovery | Semi-structured insight interviews, contextual inquiry, affinity diagramming |
| Requirements | Persona development, root cause analysis, scenario mapping |
| Prototyping | Low-fidelity Miro prototype (conceptual model: Digital Household Whiteboard) |
| Evaluation | Wizard of Oz usability testing, Think-Aloud Protocol |
| Iteration | Revised high-fidelity mockups with bimodal colour hierarchy |
| Heuristic Evaluation | Nielsen's 10 Heuristics applied to revised prototype |

---

## Key Design Concepts

### Bimodal System Personality (Selective Anthropomorphism)
HomeRun switches between two tones depending on context:
- **Machine Auditor** — strict, neutral, official tone for high-friction tasks (bills, overdue chores)
- **Friendly Host** — warm, conversational tone for onboarding, completions, and social events

### Two Core Personas
| | The Organiser (Chloe) | The Follower (Ryan) |
|---|---|---|
| Mental Model | Collective-centric | Self-centric |
| Pain Point | Emotional labour of policing housemates | Notification fatigue & ambiguous standards |
| Dashboard Need | Holistic ledger & master inventory view | Minimalist personal task checklist |

### Core Features
- **Centralised Overview Dashboard** — aggregated at-a-glance home hub with traffic-light urgency system
- **Financial Records** — transparent shared ledger with explicit "Settle Debt" actions
- **Household Chores** — standardised sub-checklists that eliminate subjective standards
- **Shared Inventory** — toggle-based stock tracking that removes the need to ask housemates directly
- **Social Calendar** — colour-coded event tagging to prevent social collisions
- **Important Documents** — pinned document storage for house rules and tenancy agreements
- **Customisable Modular Dashboard** — users pin only the widgets relevant to their persona

---

## Repository Structure

````
homerun-hci/
├── README.md
├── report/
│   └── NM3243_T2_Group1_FinalReport.pdf
├── presentations/
│   ├── 01_problem space and features.pdf
│   ├── 02_user research.pdf
│   ├── 03_data gathering plan.pdf
|   ├── 04_personas and requirements.pdf
|   ├── 05_conceptual design and prototyping.pdf
│   └── 06_user testing and evaluation.pdf
├── research/
│   ├── Appendix A_informed consent template.pdf
│   ├── Appendix B_insight interview questions.pdf
│   └── Appendix C_insight interview transcripts.pdf
├── design/
│   └── Appendix D_storyboards.pdf
|
└── evaluation/
    └── Appendix F_Prototype Testing Interview Template & Task Sheet.pdf
````

---

## Research Participants

Four participants across two Singapore households were interviewed and subsequently recruited for usability testing, enabling dyad analysis of shared household dynamics.

| Participant | Context | Persona Type |
|---|---|---|
| Isaac | NTU Hall of Residence (2-pax) | The Organiser |
| Mark | NTU Hall of Residence (2-pax) | The Follower |
| Xingchen | Off-campus co-living (4-pax) | Independent / Transactional |
| Zixuan | NUS UTown Residence (4-pax) | Close-friends household |

---

## Key Findings

1. **The Fragility of the Human System** — Every household had an informal "Coordinator" carrying the full cognitive load. When they stop pushing, shared accountability collapses.
2. **The Social Utility of "Cold" Automation** — Users explicitly preferred automated reminders over peer-to-peer messages for financial and chore-related tasks, citing machine heuristics (perceived objectivity of automated systems).
3. **Incident-Prevention over Efficiency** — The perceived value of a coordination tool is not daily time-saving, but preventing embarrassing or costly social collisions.

---

## Tools & Methods

- **Prototyping:** Figma, Miro
- **Research:** Semi-structured interviews, Wizard of Oz testing, Think-Aloud Protocol
- **Analysis:** Inductive thematic mapping, affinity diagramming, Nielsen's Heuristic Evaluation

---

## Team

NM3243 Tutorial 2, Group 1 — National University of Singapore, AY2025/26

---

## Course

**NM3243 Interaction Design**
Department of Communications and New Media, NUS
