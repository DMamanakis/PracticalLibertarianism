# Practical Libertarianism Project Requirements Specification

> **Authoritative project record:** This file is the organizational chart, content
> inventory, traceability record, and work backlog for the project. When another
> planning document conflicts with this file, this file governs.

## 1. Project Definition

**Purpose:** Present a practical libertarian framework grounded in the United
States Constitution, original public meaning, federalism, individual liberty,
and limited government.

**Mission:** Propose reforms that distribute authority, improve accountability
and transparency, and preserve workable constitutional institutions rather than
discarding them.

**Audience:** General readers, policymakers, legislators, constitutional
scholars, and students.

**Publication goal:** A publishable five-part book supported by independently
verifiable research and concrete legal and policy proposals.

## 2. How to Use This File

1. Add every planned chapter or supporting document to the appropriate register.
2. Give it the next available identifier in its part and hundred block.
3. Add missing sections, questions, research, citations, and review needs beneath
   the parent item as numbered work items.
4. Record dependencies in both places: here and in the working document.
5. Check off completed work here. Update the working document's header at the
   same time when practical; if the two disagree, reconcile them during review.
6. Never reuse a retired identifier. Mark it `CANCELLED` or `SUPERSEDED` and link
   to its replacement.

This file tracks content readiness. GitHub issues may be used for discussion or
short-term assignments, but they do not replace this record.

## 3. Identifier Standard

### 3.1 Format

`TYPE-P#-C### - Title or description`

The `C` segment uses at least three digits. It may expand to four digits when a
part contains ten or more parent documents (for example, `C1000`).

| Segment | Meaning | Examples |
| --- | --- | --- |
| `TYPE` | Kind of project material | `MC`, `RP`, `PR`, `R`, `PJ` |
| `P#` | Book part primarily supported; `P0` is project-wide/front matter | `P0`–`P5` |
| `C###` or `C####` | Parent document or work item within a hundred block | `C100`, `C101`, `C1000` |

### 3.2 Type Codes

| Code | Material | Repository location |
| --- | --- | --- |
| `MC` | Manifesto chapter or front matter | `Manifesto Chapters/` or project root |
| `RP` | Research paper | `Research Papers/` |
| `PR` | Proposal, model, amendment, or transition plan | `Proposals/` |
| `R` | Reference or primary-source record | `references/` |
| `PJ` | Project-wide editorial, publishing, or repository work | `docs/` or root |

### 3.3 Hundred Blocks

The base hundred is the parent document. Its following 99 identifiers are
reserved for sections, questions, or work belonging to it.

- `MC-P1-C100` — Part 1, Chapter 1
- `MC-P1-C101` through `MC-P1-C199` — work belonging to Chapter 1
- `MC-P1-C200` — Part 1, Chapter 2
- `MC-P1-C201` through `MC-P1-C299` — work belonging to Chapter 2

Use the same rule independently in every type and part. Do not infer a formal
relationship merely because two items share a number; record relationships in
`Supports`, `Depends on`, or `Related` fields.

### 3.4 Statuses

Use exactly one status per parent item:

`PLANNED` → `OUTLINED` → `RESEARCHING` → `DRAFTING` → `REVIEW` →
`CITATIONS COMPLETE` → `READY` → `PUBLISHED`

Use `BLOCKED`, `SUPERSEDED`, or `CANCELLED` only when needed. A checked work item
means that task is complete; it does not by itself mean the parent is publication
ready.

## 4. Required Working-Document Header

Place this block at the top of each new manuscript chapter, research paper, or
proposal. Word documents may use the same labels as a small opening table.

```text
ID: MC-P1-C100
Title: Why Liberty Requires Government
Status: OUTLINED
Supports: —
Depends on: RP-P1-C100; R-P1-C100
Open work: MC-P1-C101; MC-P1-C102
Last reviewed: YYYY-MM-DD
```

`Open work` may become temporarily stale. The detailed entries in this file are
the authoritative backlog.

## 5. Definition of Ready

A chapter is `READY` only after the applicable work is complete:

- [ ] Purpose and central claim are clear.
- [ ] Constitutional framework and present law are accurate.
- [ ] Historical context is sufficient and relevant.
- [ ] Facts, analysis, opinion, and recommendations are distinguishable.
- [ ] Major counterarguments and risks are addressed fairly.
- [ ] Proposed reforms include authority, implementation, and transition needs.
- [ ] Factual and legal claims have traceable citations.
- [ ] Related research papers, references, and proposals are linked both ways.
- [ ] Legal/constitutional review is complete when applicable.
- [ ] Technical/factual and editorial reviews are complete.
- [ ] Hostile Review Process is complete.

## 6. Manuscript Organizational Chart and Backlog

The ordering below is the current canonical book structure. Titles may change;
identifiers remain stable.

### Part 0 — Front Matter

#### MC-P0-C000 - Governing Documents

- **Status:** DRAFTING
- **Files:** `PROJECT_CHARTER.md`, `PROJECT_REQUIREMENTS_SPECIFICATION.md`,
  `AGENTS.md`, `CHANGELOG.md`, `HOSTILE_REVIEW.md`, `README.md`, and
  `STYLE_GUIDE.md`
- [x] MC-P0-C001 - Establish the Project Charter.
- [x] MC-P0-C002 - Establish the authoritative Project Requirements Specification.
- [x] MC-P0-C003 - Define contributor roles and responsibilities in `AGENTS.md`.
- [x] MC-P0-C004 - Establish the project changelog.
- [x] MC-P0-C005 - Define the Hostile Review process.
- [x] MC-P0-C006 - Describe the project scope, structure, and publication goals in
      `README.md`.
- [x] MC-P0-C007 - Establish the project Style Guide.
- [ ] MC-P0-C008 - Review all governing documents against the completed manuscript.

#### MC-P0-C100 - Title Page

- **Status:** PLANNED
- **File:** `Title_Page.md`
- [ ] MC-P0-C101 - Formal identification of the work.

#### MC-P0-C200 - Copyright

- **Status:** PLANNED
- **File:** `Copyright.md`
- [ ] MC-P0-C201 - Self Explanatory.

#### MC-P0-C300 - Table of Contents

- **Status:** PLANNED
- **File:** `Table_of_Contents.md`
- [ ] MC-P0-C301 - The book's complete listing of sections, chapters, and materials.

#### MC-P0-C400 - Forward

- **Status:** PLANNED
- **File:** `Forward.md`
- [ ] MC-P0-C401 - Introduction by [someone].

#### MC-P0-C500 - Preface

- **Status:** DRAFTING
- **File:** `Manifesto Chapters/Part 0 - Front Matter/Preface.txt`
- [x] MC-P0-C501 - Explain my personal reason for writing this book.
- [ ] MC-P0-C502 — Explain why another book on libertarianism is needed.
- [ ] MC-P0-C503 — Explain the practical problem this book attempts to solve.
- [ ] MC-P0-C504 — Describe the intended audience.
- [ ] MC-P0-C505 — Set expectations for the tone and approach of the book.

#### MC-P0-C600 - Purpose and Method

- **Status:** DRAFTING
- **File:** `Manifesto Chapters/Part 0 - Front Matter/Purpose_and_Method.txt`
- **Sources:** `docs/Conversations/Conversation 0001.txt` through
  `Conversation 0004.txt`
- [ ] MC-P0-C601 - Explain the book's purpose and methodology.
- [ ] MC-P0-C602 - Explain the intended audience.
- [ ] MC-P0-C603 - Explain the scope of the work.
- [ ] MC-P0-C604 - Explain why this methodology was chosen.
- [ ] MC-P0-C605 - Explain the relationship between philosophy and implementation.
- [ ] MC-P0-C606 — State the primary objective of the book.
- [ ] MC-P0-C607 — Explain why practical solutions are emphasized over ideological purity.
- [ ] MC-P0-C608 — Explain that constitutional constraints are treated as governing design requirements.
- [ ] MC-P0-C609 — Explain that proposals are intended to be implementable.
- [ ] MC-P0-C610 — Explain the relationship between liberty and responsibility.
- [ ] MC-P0-C611 — Explain how proposals are evaluated throughout the book.

**Acceptance criteria:**

- [ ] The Constitution is presented as the controlling framework rather than a
      source of optional guidance.
- [ ] Readers understand that proposed reforms must fit within existing
      constitutional authority unless accompanied by a proposed amendment.
- [ ] The distinction between constitutional interpretation and policy
      preference is made explicit.

#### MC-P0-C700 - How to Read This Book

- **Status:** PLANNED
- **File:** `How_to_Read_This_Book.md`
- [ ] MC-P0-C701 - Give the reader tips for how to understand the book.

#### MC-P0-C800 - What This Book Is Not

- **Status:** PLANNED
- **File:** `Manifesto Chapters/Part 0 - Front Matter/What_This_Book_Is_Not.txt`
- [ ] MC-P0-C801 - Distinguish from anarchism.
- [ ] MC-P0-C802 - Distinguish from authoritarian conservatism.
- [ ] MC-P0-C803 - Distinguish from partisan politics.
- [ ] MC-P0-C804 - Explain why ideological purity is not the objective.
- [ ] MC-P0-C805 — Explain the organization of the book.
- [ ] MC-P0-C806 — Explain how Parts, Chapters, Research Papers, and Proposals relate to each other.
- [ ] MC-P0-C807 — Explain how constitutional references are used.
- [ ] MC-P0-C808 — Explain the distinction between philosophy, policy, and implementation.

#### MC-P0-C900 - Definitions

- **Status:** PLANNED
- **File:** `Manifesto Chapters/Part 0 - Front Matter/Definitions.txt`
- [ ] MC-P0-C901 - Define key terms and concepts used in the book.
- [ ] MC-P0-C902 — Define Liberty.
- [ ] MC-P0-C903 — Define Rights.
- [ ] MC-P0-C904 — Define Government.
- [ ] MC-P0-C905 — Define Federalism.
- [ ] MC-P0-C906 — Define Originalism.
- [ ] MC-P0-C907 — Define Enumerated Powers.
- [ ] MC-P0-C908 — Define Due Process.
- [ ] MC-P0-C909 — Define Property Rights.

#### MC-P0-C1000 - Methodology

- **Status:** PLANNED
- **File:** `Manifesto Chapters/Part 0 - Front Matter/Methodology.txt`
- [ ] MC-P0-C1001 - Explain original public meaning and interpretive limits.
- [ ] MC-P0-C1002 - Explain enumerated powers.
- [ ] MC-P0-C1003 - Explain federalism and reserved powers.
- [ ] MC-P0-C1004 - Explain burden of proof for proposed reforms.
- [ ] MC-P0-C1005 - Explain constitutional hierarchy.
- [ ] MC-P0-C1006 - Explain evidence hierarchy.
- [ ] MC-P0-C1007 - Distinguishing opinion from recommendation.
- [ ] MC-P0-C1008 - Explain what constitutes a constitutional amendment vs legislation.
- [ ] MC-P0-C1009 - Explain how competing principles are evaluated.
- [ ] MC-P0-C1010 — Distinguish constitutional amendments from legislation.
- [ ] MC-P0-C1011 — Explain how historical evidence is evaluated.
- [ ] MC-P0-C1012 — Explain how conflicting principles are resolved.
- [ ] MC-P0-C1013 — Explain why constitutional interpretation precedes policy preferences.
- [ ] MC-P0-C1014 — Explain why implementation matters as much as philosophy.

#### MC-P0-C1100 - Bibliography

- **Status:** PLANNED
- **File:** `Bibliography.md`
- [ ] MC-P0-C1101 - Select and document the project citation style.
- [ ] MC-P0-C1102 - Create the consolidated bibliography.

### Part 1 — Foundations

#### MC-P1-C100 - Why Liberty Requires Government

- **Status:** DRAFTING
- [x] MC-P1-C101 - Establish the core practical-libertarian philosophy.
- [x] MC-P1-C102 - Explain the legitimate role of government.
- [ ] MC-P1-C103 - Research Locke, Jefferson, and Madison.
- [ ] MC-P1-C104 - Develop civic virtue and personal responsibility.
- [ ] MC-P1-C105 - Address the distinction between practical libertarianism and anarchy.

#### MC-P1-C200 - Constitutional Originalism

- **Status:** DRAFTING
- [x] MC-P1-C201 - Establish the originalism framework.
- [x] MC-P1-C202 - Address enumerated powers.
- [ ] MC-P1-C203 - Add separation-of-powers analysis.
- [ ] MC-P1-C204 - Address principal objections to originalism.

#### MC-P1-C300 - Federalism

- **Status:** DRAFTING
- [x] MC-P1-C301 - Establish the lowest-practical-level principle.
- [ ] MC-P1-C302 - Add relevant federalism case law.
- [ ] MC-P1-C303 - Address state constitutions and local government.

#### MC-P1-C400 - Rights and Responsibilities

- **Status:** DRAFTING
- [x] MC-P1-C401 - Establish rights-and-responsibilities framework.
- [ ] MC-P1-C402 - Develop natural-rights analysis.
- [ ] MC-P1-C403 - Explain due process and equal protection.

#### MC-P1-C500 - Property Rights

- **Status:** DRAFTING
- [x] MC-P1-C501 - Address private property.
- [x] MC-P1-C502 - Address self-ownership.
- [ ] MC-P1-C503 - Address contracts.
- [ ] MC-P1-C504 - Address eminent domain.

### Part 2 — Domestic Government

#### MC-P2-C100 - Policing and Search Warrants

- **Status:** DRAFTING
- [x] MC-P2-C101 - Address policing principles.
- [x] MC-P2-C102 - Address warrants.
- [ ] MC-P2-C103 - Address qualified immunity.
- [ ] MC-P2-C104 - Add constitutional and case-law support.

#### MC-P2-C200 - Criminal Justice and Sentencing

- **Status:** PLANNED
- [ ] MC-P2-C201 - Define the criminal-justice scope.
- [ ] MC-P2-C202 - Address sentencing reform.
- [ ] MC-P2-C203 - Address civil liability and tort reform.

#### MC-P2-C300 - Immigration and Borders

- **Status:** DRAFTING
- [x] MC-P2-C301 - Address border security.
- [x] MC-P2-C302 - Address legal immigration and due process.
- [ ] MC-P2-C303 - Address asylum.
- [ ] MC-P2-C304 - Address visa reform.

#### MC-P2-C400 - Education

- **Status:** DRAFTING
- [x] MC-P2-C401 - Address school choice and local control.
- [x] MC-P2-C402 - Address viewpoint-neutral classrooms.
- [ ] MC-P2-C403 - Address higher education.

#### MC-P2-C500 - Executive Agencies and the Administrative State

- **Status:** PLANNED
- [ ] MC-P2-C501 - Define permissible executive authority.
- [ ] MC-P2-C502 - Analyze the administrative state.
- [ ] MC-P2-C503 - Address executive orders and emergency powers.

#### MC-P2-C600 - The Judiciary

- **Status:** PLANNED
- [ ] MC-P2-C601 - Define the chapter scope and constitutional questions.

#### MC-P2-C700 - Taxation and the Budget Process

- **Status:** PLANNED
- [ ] MC-P2-C701 - Address income, property, and consumption taxes.
- [ ] MC-P2-C702 - Address the federal budget process.

#### MC-P2-C800 - Health and Welfare

- **Status:** PLANNED
- [ ] MC-P2-C801 - Address healthcare.
- [ ] MC-P2-C802 - Address welfare, disability, and poverty.

#### MC-P2-C900 - Commerce, Infrastructure, and Environmental Policy

- **Status:** PLANNED
- [ ] MC-P2-C901 - Define the constitutional scope of commerce policy.
- [ ] MC-P2-C902 - Address infrastructure.
- [ ] MC-P2-C903 - Address environmental policy.

### Part 3 — Constitutional Reform

#### MC-P3-C100 - Federal Lands

- **Status:** DRAFTING
- **Depends on:** RP-P3-C100; PR-P3-C100
- [x] MC-P3-C101 - Develop Property Clause analysis.
- [x] MC-P3-C102 - Address BLM land and national parks.
- [ ] MC-P3-C103 - Address water rights.
- [ ] MC-P3-C104 - Address tribal issues.
- [ ] MC-P3-C105 - Complete citations and counterarguments.

#### MC-P3-C200 - National Defense and a Distributed Military

- **Status:** DRAFTING
- **Depends on:** PR-P3-C200
- [x] MC-P3-C201 - Develop the distributed-defense concept.
- [ ] MC-P3-C202 - Address militia structure.
- [ ] MC-P3-C203 - Address the National Guard.
- [ ] MC-P3-C204 - Address foreign-policy implications.

#### MC-P3-C300 - Voting Rights and Election Integrity

- **Status:** DRAFTING
- **Depends on:** RP-P3-C300; PR-P3-C300
- [x] MC-P3-C301 - Address voting rights and state administration.
- [x] MC-P3-C302 - Address proof of citizenship and voter identification.
- [x] MC-P3-C303 - Address mail voting, audits, and roll maintenance.
- [x] MC-P3-C304 - Address election crimes.
- [ ] MC-P3-C305 - Analyze the VRA, NVRA, HAVA, and SAVE Act.
- [ ] MC-P3-C306 - Analyze controlling Supreme Court cases.
- [ ] MC-P3-C307 - Address campaign finance.
- [ ] MC-P3-C308 - Address redistricting.

#### MC-P3-C400 - Electoral College Reform

- **Status:** DRAFTING
- **Depends on:** RP-P3-C400; PR-P3-C400
- [x] MC-P3-C401 - Develop proportional electoral-weight concept.
- [x] MC-P3-C402 - Develop ranked-choice integration concept.
- [ ] MC-P3-C403 - Research the House contingency process.
- [ ] MC-P3-C404 - Complete mathematical examples.

#### MC-P3-C500 - Congressional Reform

- **Status:** PLANNED
- [ ] MC-P3-C501 - Define representation and institutional reforms.
- [ ] MC-P3-C502 - Evaluate term limits.

#### MC-P3-C600 - Budget and Fiscal Reform

- **Status:** PLANNED
- [ ] MC-P3-C601 - Evaluate balanced-budget mechanisms.
- [ ] MC-P3-C602 - Define transition and enforcement requirements.

### Part 4 — Economic Policy

#### MC-P4-C100 - Sound Money

- **Status:** DRAFTING
- **Depends on:** RP-P4-C100
- [x] MC-P4-C101 - Establish the sound-money foundation.
- [ ] MC-P4-C102 - Add historical and empirical support.

#### MC-P4-C200 - Banking, Inflation, and the Federal Reserve

- **Status:** PLANNED
- [ ] MC-P4-C201 - Address banking institutions.
- [ ] MC-P4-C202 - Address inflation.
- [ ] MC-P4-C203 - Address the Federal Reserve.

#### MC-P4-C300 - Debt and Social Security

- **Status:** PLANNED
- [ ] MC-P4-C301 - Address public debt.
- [ ] MC-P4-C302 - Develop Social Security reform options.

#### MC-P4-C400 - Property Tax

- **Status:** PLANNED
- [ ] MC-P4-C401 - Define the constitutional and policy analysis.

#### MC-P4-C500 - Free Markets and Trade

- **Status:** PLANNED
- [ ] MC-P4-C501 - Establish the free-market framework.
- [ ] MC-P4-C502 - Address domestic and international trade.

### Part 5 — Technology and Future Policy

#### MC-P5-C100 - Artificial Intelligence

- **Status:** PLANNED
- [ ] MC-P5-C101 - Define liberty, accountability, and governance questions.

#### MC-P5-C200 - Privacy

- **Status:** PLANNED
- [ ] MC-P5-C201 - Define privacy rights and governmental limits.

#### MC-P5-C300 - Cybersecurity

- **Status:** PLANNED
- [ ] MC-P5-C301 - Define public and private responsibilities.

#### MC-P5-C400 - Energy

- **Status:** PLANNED
- [ ] MC-P5-C401 - Define the constitutional and market framework.

#### MC-P5-C500 - Infrastructure and Data Centers

- **Status:** PLANNED
- [ ] MC-P5-C501 - Address infrastructure responsibilities.
- [ ] MC-P5-C502 - Address data-center energy, land, and water demands.

## 7. Research Paper Register and Backlog

#### RP-P1-C100 - Foundations: Philosophical and Founding Sources

- **Status:** PLANNED
- **Supports:** MC-P1-C100; MC-P1-C200; MC-P1-C300
- [ ] RP-P1-C101 - Research Locke, Jefferson, Madison, the Federalists, and Anti-Federalists.

#### RP-P1-C200 - Federalism Case Law

- **Status:** PLANNED
- **Supports:** MC-P1-C300
- [ ] RP-P1-C201 - Identify and analyze controlling federalism decisions.

#### RP-P3-C100 - Property Clause and Federal Lands

- **Status:** PLANNED
- **Supports:** MC-P3-C100; PR-P3-C100
- [ ] RP-P3-C101 - Complete constitutional text and founding-era research.
- [ ] RP-P3-C102 - Complete Supreme Court and statutory research.

#### RP-P3-C300 - Election Integrity Legal Survey

- **Status:** PLANNED
- **Supports:** MC-P3-C300; PR-P3-C300
- [ ] RP-P3-C301 - Analyze the VRA, NVRA, HAVA, and SAVE Act.
- [ ] RP-P3-C302 - Analyze Shelby County, Brnovich, Crawford, and related cases.

#### RP-P3-C400 - Electoral College Mathematical Model

- **Status:** PLANNED
- **Supports:** MC-P3-C400; PR-P3-C400
- [ ] RP-P3-C401 - Model proportional allocation and ranked-choice scenarios.
- [ ] RP-P3-C402 - Test edge cases and the House contingency process.

#### RP-P4-C100 - Sound Money Historical Analysis

- **Status:** PLANNED
- **Supports:** MC-P4-C100
- [ ] RP-P4-C101 - Assemble historical, monetary, and empirical evidence.

#### RP-P2-C500 - Administrative State Analysis

- **Status:** PLANNED
- **Supports:** MC-P2-C500
- [ ] RP-P2-C501 - Analyze delegation, executive authority, and judicial doctrine.

## 8. Proposal Register and Backlog

#### PR-P3-C100 - Federal Lands Constitutional Amendment

- **Status:** DRAFTING
- **Supports:** MC-P3-C100
- [ ] PR-P3-C101 - Draft operative amendment text.
- [ ] PR-P3-C102 - Add transition, implementation, and fiscal analysis.

#### PR-P3-C200 - Distributed Defense Constitutional Amendment

- **Status:** DRAFTING
- **Supports:** MC-P3-C200
- [ ] PR-P3-C201 - Draft operative amendment text.
- [ ] PR-P3-C202 - Add militia, National Guard, command, and transition analysis.

#### PR-P3-C300 - Election Reform Constitutional Amendment

- **Status:** DRAFTING
- **Supports:** MC-P3-C300
- [ ] PR-P3-C301 - Draft operative amendment text.
- [ ] PR-P3-C302 - Identify federal, state, and local authority.

#### PR-P3-C400 - Electoral Allocation and Ranked-Choice Implementation

- **Status:** DRAFTING
- **Supports:** MC-P3-C400
- [ ] PR-P3-C401 - Draft the constitutional mechanism.
- [ ] PR-P3-C402 - Draft federal implementation legislation.
- [ ] PR-P3-C403 - Draft model state legislation.

#### PR-P3-C500 - Election Implementation Roadmap

- **Status:** PLANNED
- **Supports:** MC-P3-C300; MC-P3-C400
- [ ] PR-P3-C501 - Define sequencing, timelines, administration, and audits.

#### PR-P3-C600 - Balanced-Budget Amendment

- **Status:** PLANNED
- **Supports:** MC-P3-C600
- [ ] PR-P3-C601 - Define scope, exceptions, enforcement, and transition.

#### PR-P2-C900 - Commerce Reform Proposal

- **Status:** PLANNED
- **Supports:** MC-P2-C900
- [ ] PR-P2-C901 - Determine whether statutory or constitutional action is required.

#### PR-P2-C700 - Tax Reform Proposal

- **Status:** PLANNED
- **Supports:** MC-P2-C700
- [ ] PR-P2-C701 - Define federal, state, and local implementation options.

## 9. Reference Register and Backlog

Reference identifiers describe sources cataloged or stored in `references/`.
Copyrighted works may be represented by bibliographic records rather than copied
into the repository.

#### R-P0-C100 - United States Constitution

- **Status:** PLANNED
- **Supports:** All constitutional chapters and proposals
- [ ] R-P0-C101 - Add canonical text or an authoritative link and citation metadata.

#### R-P0-C200 - Federal Statutes

- **Status:** PLANNED
- [ ] R-P0-C201 - Establish a consistent statute-record template.

#### R-P0-C300 - Supreme Court Decisions

- **Status:** PLANNED
- [ ] R-P0-C301 - Establish a case record with citation, holding, and supported items.

#### R-P0-C400 - Founding and Historical Papers

- **Status:** PLANNED
- [ ] R-P0-C401 - Catalog the Federalist Papers, Anti-Federalists, and founding debates.

#### R-P0-C500 - Government Reports and Data

- **Status:** PLANNED
- [ ] R-P0-C501 - Catalog CBO, CRS, agency, and other authoritative materials.

#### R-P0-C600 - Books and Secondary Sources

- **Status:** PLANNED
- [ ] R-P0-C601 - Create bibliographic records and usage notes.

## 10. Project-Wide Backlog

#### PJ-P0-C100 - Content Intake and Inventory

- **Status:** DRAFTING
- [ ] PJ-P0-C101 - Inventory each new or recovered document in this specification.
- [ ] PJ-P0-C102 - Classify material as manuscript, research, proposal, reference, or project record.
- [ ] PJ-P0-C103 - Reconcile prior ChatGPT conversations and drafts with the canonical outline.

#### PJ-P0-C200 - Citation System

- **Status:** PLANNED
- [ ] PJ-P0-C201 - Choose a citation style.
- [ ] PJ-P0-C202 - Define footnote, bibliography, URL, access-date, and archival rules.
- [ ] PJ-P0-C203 - Create citation and bibliography templates.

#### PJ-P0-C300 - Traceability Review

- **Status:** PLANNED
- [ ] PJ-P0-C301 - Link every manuscript chapter to supporting research and proposals.
- [ ] PJ-P0-C302 - Link every research paper, proposal, and reference back to supported chapters.
- [ ] PJ-P0-C303 - Audit working-document headers against this file.

#### PJ-P0-C400 - Editorial and Legal Review

- **Status:** PLANNED
- [ ] PJ-P0-C401 - Review completed drafts for counterarguments.
- [ ] PJ-P0-C402 - Complete constitutional/legal review.
- [ ] PJ-P0-C403 - Complete factual/technical review.
- [ ] PJ-P0-C404 - Complete editorial consistency review.

#### PJ-P0-C500 - Publishing

- **Status:** PLANNED
- [ ] PJ-P0-C501 - Define manuscript assembly and export process.
- [ ] PJ-P0-C502 - Create index and final bibliography.
- [ ] PJ-P0-C503 - Define release, edition, and versioning conventions.

## 11. Template for a New Parent Item

Copy this block into the appropriate register and assign the next open hundred:

```markdown
#### MC-P#-C### - Title

- **Status:** PLANNED
- **File:** `path/to/file` (when created)
- **Supports:** IDs or `—`
- **Depends on:** IDs or `—`
- [ ] MC-P#-C##1 - First identifiable work item.
- [ ] MC-P#-C##2 - Second identifiable work item.
```

Before adding an item, search this file for its intended identifier and subject.
Append new work within the parent's reserved block; do not renumber existing IDs.
