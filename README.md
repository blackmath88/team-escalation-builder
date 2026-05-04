# Team Protection & Escalation Builder

A lightweight single-file HTML workshop tool for helping university teams, ethics committees, research groups, and sensitive governance bodies co-create their own protection and escalation model.

The tool is inspired by the interaction logic of the existing `change-management-platform-demo` project, but it must remain much smaller and more focused.

This is not a multi-week change management platform.

It is a compact 45–90 minute guided team-builder.

---

## Purpose

The tool helps teams define:

- when concerns should remain in normal team dialogue
- when early signals should be surfaced
- when protected consultation is needed
- when formal clarification is required
- when immediate protection or independent review is necessary

The central framing is:

> Escalation is not a sign of failure.  
> Escalation is a pre-agreed protection path when people, roles, or decisions come under pressure.

---

## Target users

- University ethics committees
- Research groups
- Governance bodies
- Public-sector teams
- Teams with strong hierarchy or power asymmetries
- Teams handling confidential, ethical, safety, or employee-protection concerns

---

## Core outcome

At the end, the team should have a copyable one-page model:

**Our Team Protection & Escalation Model**

Including:

- purpose
- context
- guiding principles
- escalation levels
- triggers
- roles and contact paths
- protection mechanisms
- documentation and confidentiality
- de-escalation criteria
- review rhythm
- open questions

---

## Build requirements

Create a complete `index.html` file.

Use:

- vanilla HTML
- embedded CSS
- embedded JavaScript
- no backend
- no build tools
- no React/Vue
- no external dependencies if possible

The file should work by opening it directly in a browser.

---

## UX requirements

The tool should feel like a calm guided workshop.

Use a five-step or seven-step flow, but keep the interface lightweight.

Recommended structure:

1. Start / Why this matters
2. Context Capture
3. Concepts
4. Escalation Levels Builder
5. Trigger Workshop
6. AI Prompt Builder
7. Final Onepager Output

The interface should include:

- step navigation
- concise educational cards
- structured input fields
- editable level cards
- selectable trigger chips
- copyable AI prompts
- live-generated onepager
- copy-to-clipboard buttons
- print option
- reset option
- localStorage autosave
- “Saved locally” indicator

---

## Design direction

Professional university / public-sector look.

Style:

- calm
- serious
- protective
- not dramatic
- not “crisis war room”
- white / soft blue base
- subtle rounded cards
- clean typography
- yellow only for AI-assisted areas

Add a privacy note:

> All inputs remain in your browser unless you copy, print, or export them.

---

## AI usage framing

AI must not be framed as a decision-maker.

Use this framing:

> AI does not decide. It helps the team reflect, sharpen language, identify blind spots, and prepare documentation.

The AI section should generate copyable prompts from the current user inputs and current escalation model.

Prompt modes:

1. Sharpen our model
2. Risk-review our model
3. Facilitate our workshop

---

## Inspiration from existing project

This tool may use interaction patterns inspired by `change-management-platform-demo`:

- guided tabs / steps
- local state flowing through the experience
- AI cue panels
- generated prompts
- copy buttons
- final export logic

But do not recreate the full platform structure.

This project should be a small standalone workshop tool.

---

## Deliverable

Create:

```text
index.html
