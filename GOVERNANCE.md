# SYD GOVERNANCE

## SydTek Scholars Development Constitution

**Version:** 0.1.0  
**Status:** Genesis Governance  
**Applies to:** SYD repository, SydTek Scholars curriculum, associated course objects, research artifacts, and project-passport infrastructure.

---

# PURPOSE

SYD is being built as both:

1. a functioning educational system, and
2. a documented experiment in how that educational system was created.

Governance therefore has two responsibilities:

**BUILD THE SYSTEM**

and

**PRESERVE THE RECORD OF HOW THE SYSTEM WAS BUILT.**

The repository should not merely show the final answer.

It should preserve enough history that a future reviewer can reconstruct:

- what existed,
- what changed,
- why it changed,
- who changed it,
- what evidence informed the decision,
- what version resulted.

---

# GOVERNANCE PRINCIPLE 1

## THE CONTROL TOWER IS THE SYSTEM OF RECORD.

The Control Tower is not merely a dashboard.

For purposes of SYD, the authoritative record should eventually connect:

- project IDs,
- course IDs,
- versions,
- owners,
- contributors,
- rights,
- NIL,
- assessments,
- revenue rules,
- payments,
- publication status,
- token relationships,
- legal status,
- academic status,
- evidence gates,
- next actions.

GitHub is one major record layer.

It is not necessarily the only record layer.

---

# GOVERNANCE PRINCIPLE 2

## CONTROL THE CORE. DISTRIBUTE THE RAILS.

The institutional core should define:

- academic standards,
- course IDs,
- assessment standards,
- rights policies,
- provenance rules,
- version controls,
- contributor attribution,
- revenue rules,
- security requirements.

Projects, instructors, creators, developers, and collaborators may build on top of those rails.

They do not need to reinvent the entire operating system.

---

# GOVERNANCE PRINCIPLE 3

## AUGMENTATION WITHOUT ABDICATION.

AI may assist:

- research,
- curriculum drafting,
- assessment generation,
- code,
- editing,
- transcription,
- classification,
- analytics,
- rights checks,
- metadata,
- documentation.

AI does not automatically receive final authority over:

- grades,
- legal rights,
- institutional policy,
- academic misconduct findings,
- financial decisions,
- NIL consent,
- contributor ownership,
- material governance changes.

Human accountability remains required.

---

# GOVERNANCE PRINCIPLE 4

## CAN ≠ MAY.

A system being technically capable of doing something does not mean it is authorized to do it.

Examples:

A smart contract may be able to transfer funds.

That does not mean it is authorized to transfer those funds.

An AI model may be able to clone a voice.

That does not mean it has permission.

A token may be technically transferable.

That does not mean it creates academic rights.

A developer may be able to change production code.

That does not mean the developer owns the underlying project.

Capability and authority are separate.

---

# GOVERNANCE PRINCIPLE 5

## EVIDENCE BEFORE SCALE.

Projects should move through gates.

Suggested stages:

**IDEA**

↓

**RESEARCH**

↓

**PROTOTYPE**

↓

**TEST**

↓

**RELEASE**

↓

**SCALE**

↓

**LICENSING / EXPANSION**

Each stage should answer:

- What evidence exists?
- What remains unknown?
- What rights are required?
- What risks exist?
- What capital is required?
- What must happen before the next gate?

A project that fails its gate may:

- pause,
- revise,
- return to research,
- or stop.

Stopping a project is a valid outcome.

---

# GOVERNANCE PRINCIPLE 6

## DO NOT HIDE FAILURE.

SYD should preserve:

- failed hypotheses,
- unsuccessful courses,
- low completion rates,
- bad assumptions,
- rejected structures,
- incorrect predictions,
- failed integrations,
- abandoned token utilities,
- poor product-market fit,
- assessment problems,
- student confusion,
- technical failures.

A failed experiment may create more useful evidence than a successful one.

---

# GOVERNANCE PRINCIPLE 7

## RIGHTS FOLLOW THE ASSET.

Every significant asset should eventually be able to answer:

- Who created this?
- Who owns this?
- Who appears in this?
- What license applies?
- What NIL rights apply?
- What music rights apply?
- What AI rights apply?
- Where can it be distributed?
- Who participates economically?

Rights should not be assumed because companies, projects, or people are affiliated.

---

# GOVERNANCE PRINCIPLE 8

## TOKEN RIGHTS ARE SEPARATE FROM INSTITUTIONAL RIGHTS.

A token may represent a documented utility.

A token does not automatically represent:

- equity,
- ownership,
- academic credit,
- admission,
- intellectual property,
- NIL,
- revenue rights,
- voting rights,
- treasury rights.

Any right must come from the instrument or agreement that actually creates that right.

---

# GOVERNANCE PRINCIPLE 9

## THE ACADEMIC RAIL REMAINS INDEPENDENT.

Academic completion should follow:

**LEARNING**

↓

**ASSESSMENT**

↓

**DEMONSTRATION**

↓

**REVIEW**

↓

**PASS / RESUBMIT / FAIL**

↓

**RECORD**

Neither money, token ownership, influence, social reach, donor status, nor personal relationship should automatically produce a passing academic result.

---

# GOVERNANCE PRINCIPLE 10

## CONTRIBUTORS SHOULD BE VISIBLE.

The system should progressively identify:

- creator,
- instructor,
- researcher,
- developer,
- producer,
- editor,
- designer,
- NIL participant,
- affiliate,
- reviewer,
- institution,
- rights owner.

The objective is to reduce invisible labor.

---

# CHANGE AUTHORITY

During the Genesis phase, the repository owner may approve direct changes.

As participation expands, material changes should increasingly use:

- issues,
- branches,
- pull requests,
- review,
- documented approvals.

---

# MATERIAL CHANGES

Examples of material changes:

- changing course learning outcomes,
- changing assessment standards,
- changing passing thresholds,
- changing revenue allocations,
- changing token rights,
- changing NIL rights,
- changing project ownership,
- changing academic claims,
- changing institutional positioning,
- changing security architecture,
- changing AI authority.

Material changes should not be silently edited without version history.

---

# NON-MATERIAL CHANGES

Examples:

- spelling,
- formatting,
- broken links,
- grammar,
- minor clarification,
- file organization.

These may use lighter review.

---

# DECISION RECORDS

For major decisions, create a decision record.

Suggested path:

`decisions/ADR-0001-title.md`

ADR = Architecture / Academic / Administrative Decision Record.

Each record should contain:

- decision ID,
- date,
- question,
- context,
- alternatives,
- decision,
- rationale,
- risks,
- evidence,
- reviewers,
- future review date.

---

# CONFLICTS OF INTEREST

A contributor should disclose material conflicts when relevant.

Examples:

- owning an asset being taught,
- creating a token being analyzed,
- receiving creator fees,
- receiving affiliate compensation,
- holding treasury authority,
- receiving sponsorship,
- receiving consulting fees,
- having ownership in a vendor being recommended.

A conflict does not automatically disqualify participation.

An undisclosed material conflict creates a credibility problem.

---

# PROJECT GOVERNANCE

Every major project should eventually receive:

## PROJECT ID

Example:

`SYD-PROJ-001`

And a Project Passport containing:

- project owner,
- project lead,
- contributors,
- rights,
- budget,
- revenue rules,
- legal status,
- release status,
- evidence gate,
- next gate.

---

# COURSE GOVERNANCE

Every course receives:

## COURSE ID

Example:

`SYD-MKT-101`

Course IDs should remain stable.

Course content receives versions.

Example:

`SYD-MKT-101 v1.0.0`

Do not create a new ID simply because one lesson changed.

---

# VERSIONING

Recommended:

## MAJOR

`2.0.0`

Use when:

- learning outcomes materially change,
- assessment architecture changes,
- the course becomes substantially different.

## MINOR

`1.1.0`

Use when:

- modules are added,
- substantial new content appears,
- a meaningful case study is added.

## PATCH

`1.0.1`

Use when:

- errors are corrected,
- wording is clarified,
- links are repaired.

---

# RESEARCH GOVERNANCE

If SYD development becomes formal human-subjects research, applicable research ethics and review requirements must be addressed before collecting or representing data as research requiring such oversight.

Ordinary product analytics should not automatically be described as human-subjects research.

Research status must be defined deliberately.

---

# GOVERNANCE EVOLUTION

The governance system may later add:

- faculty senate,
- curriculum committee,
- research committee,
- ethics committee,
- technical architecture committee,
- student representation,
- external advisory board,
- legal review,
- accreditation review.

Do not pretend those bodies exist before they actually exist.

---

# GENESIS AUTHORITY

During Day 0:

**Repository owner = provisional executive authority.**

That authority exists to build the initial system.

It is not a claim that one person must permanently control every future academic, technical, or institutional decision.

Governance should mature as the institution matures.

---

# FINAL GOVERNANCE RULE

When uncertain, preserve:

**THE HUMAN**

**THE RIGHTS**

**THE EVIDENCE**

**THE RECORD**

Then make the decision.