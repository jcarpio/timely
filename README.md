# Timely — A Better Timetable Starts with a Conversation

**Product concept | October 2026**

## Executive summary

Timely is a conversational school scheduling assistant designed for schools, colleges, academic departments, and other education providers. Instead of requiring administrators to learn a complex scheduling interface, Timely lets them share an existing timetable and explain their requirements in natural language.

A user might upload a photo of a printed timetable and say: **“Make Fridays free for Ms. Taylor, keep science practicals together, and change as little else as possible.”** Timely interprets the request, identifies missing information, checks competing requirements, and proposes an updated timetable for human review.

The promise is simple: **less manual scheduling, fewer avoidable conflicts, and clearer decisions.**

> **Product status:** This document describes a proposed product and intended experience. The accompanying HTML site is a marketing prototype with an illustrative, non-operational scenario selector. Production performance, supported imports, and optimization outcomes require implementation and validation.

## The problem

Timetables sit at the intersection of dozens of competing realities: subject hours, teachers working across groups, classroom capacity, specialist facilities, part-time availability, student commitments, linked lessons, and sudden timetable changes.

Even when a school already has a workable schedule, introducing a single new condition can create cascading changes. Conventional tools may require repetitive manual adjustments, rigid forms, or specialist knowledge. Existing schedules are frequently shared in spreadsheets, PDFs, or photos rather than reusable structured data.

## The solution

Timely offers a human-centered scheduling workflow:

1. **Share a timetable.** Upload a photo, screenshot, or spreadsheet, or start by entering class groups, subjects, teachers, and session counts.
2. **Review what was recognized.** The assistant presents the extracted timetable and requests clarification for ambiguous cells or missing details.
3. **Explain the desired changes.** Users speak or type ordinary requests, from hard requirements to soft preferences.
4. **Validate the rules.** Timely checks that teacher, group, subject, and room requirements have been understood, and flags missing or contradictory inputs.
5. **Explore feasible schedules.** The scheduling service attempts to produce valid alternatives under the confirmed requirements and stated priorities.
6. **Review and refine.** Users compare alternatives with the original, inspect moved lessons, and request further refinements.
7. **Approve and export.** After review, the school can adopt and distribute the approved schedule through supported export formats.

## Example user journey

**Context:** A secondary school administrator uploads a photograph of a Year 7 timetable.

**Administrator:** “This is our current timetable. Ms. Taylor needs Fridays off, and Science should have a two-period practical session.”

**Timely:** “I have recognized five school days and six lessons per day. Does Ms. Taylor teach other year groups? And is the double Science lesson mandatory or preferred?”

**Administrator:** “She also teaches Year 8. The consecutive Science sessions are mandatory. Please try to preserve the existing schedule.”

**Timely:** “I'll consider both year groups, maintain weekly subject requirements, avoid double-booking teachers or rooms, and prioritize minimal changes. I’ll show you any requirements that cannot be met together.”

**Proposed result:** A new timetable with moved lessons highlighted, a clear summary of the changes, and an opportunity to revise further.

*This is an illustrative user journey, not the output of a deployed system.*

## Use cases

### 1. Teacher availability and working patterns

**Request:** “Ms. Taylor is unavailable on Fridays and Mr. Harris works mornings only.”

**Value:** Coordinate across class groups without creating teacher conflicts; make constraints visible across the whole schedule.

### 2. Consecutive lessons and practical sessions

**Request:** “Science needs two consecutive lessons in the lab every week.”

**Value:** Reflect the actual requirements of experimental and workshop-based teaching.

### 3. Shared rooms and specialist equipment

**Request:** “The computer lab cannot be assigned to two classes at the same time.”

**Value:** Include resource availability alongside teachers and class commitments.

### 4. Minimal disruption after a change

**Request:** “A teacher's availability has changed. Please keep everything else as close to the original as possible.”

**Value:** Reduce avoidable movement of lessons and provide a clear before-and-after comparison.

### 5. Academic departments and higher education

**Request:** “Avoid overlaps between compulsory modules and reserve a weekly seminar room.”

**Value:** Coordinate lecturers, cohorts, modules, and spaces across multiple programs.

### 6. Preferences versus strict requirements

**Request:** “Avoid Maths during the final period if possible, but ensure no teacher is double-booked.”

**Value:** Distinguish essential constraints from desirable choices and show the compromises necessary to arrive at a workable schedule.

### 7. Timetable negotiation and scenario planning

**Request:** “Show me one version with Wednesday afternoons free and another with fewer teacher gaps.”

**Value:** Compare alternatives with explicit trade-offs rather than arguing from disconnected spreadsheets.

## What makes the experience different

- **Conversation first:** Administrators express needs in their own words rather than translating them into unfamiliar settings.
- **Starts from what already exists:** The intended photo/screenshot workflow makes legacy timetables useful as a starting point.
- **Asks when uncertain:** Ambiguous recognition, incomplete data, and conflicting requests are surfaced instead of guessed away.
- **Explains changes:** Each proposal can identify which lessons moved and why.
- **Supports iteration:** Follow-up requests become refinements to the same scheduling problem, not a complete restart.
- **Human approval:** Schools retain authority over the final timetable.

## Product principles

1. **No silent assumptions.** Critical unknowns must be confirmed.
2. **Requirements remain auditable.** Users can inspect the conditions that guide scheduling.
3. **Feasibility is not guaranteed.** Incompatible requirements should receive a useful explanation, not an invented solution.
4. **Privacy by design.** School data and uploaded images require appropriate access controls, retention limits, and secure handling.
5. **Transparent trade-offs.** A preferred option should be distinguishable from a mandatory rule.
6. **Review before adoption.** Proposed schedules are not automatically published.

## Target customers and decision makers

**Primary users:** Timetable coordinators, school administrators, department heads, academic program managers, and operations teams.

**Likely buyers:** School leadership teams, school networks, colleges, universities, and education management organizations.

**Potential initial segment:** Small and medium-sized schools or departments that already manage schedules through spreadsheets and need a more approachable way to handle changes.

## Illustrative product capabilities

| Area | Proposed capability | Why it matters |
| --- | --- | --- |
| Input | Images, screenshots, spreadsheets and manual entry | Low-friction onboarding |
| Conversation | Requests and corrections in natural language | Accessible to non-specialists |
| Validation | Missing-data and conflict detection | Avoid misleading outputs |
| Scheduling | Feasible alternatives under confirmed constraints | More reliable planning |
| Change control | Minimize disruption where possible | Operational continuity |
| Comparison | Before/after views and explanations | Trust and reviewability |
| Exports | Printable timetable, spreadsheet, and shareable formats | Fits existing school workflows |
| Administration | Permissions and approval workflow | Institutional oversight |

**Note:** These are roadmap capabilities, not claims that all features have been implemented.

## Suggested pilot

An initial pilot could involve one department or a small school with a limited number of class groups and a verified baseline schedule.

**Pilot scope**

- Import or reconstruct one existing timetable.
- Confirm teacher, subject, group, and room information.
- Support a small catalog of frequent scheduling requests.
- Generate candidate schedules and compare them with the baseline.
- Collect coordinator feedback on clarity, effort saved, and usefulness.

**Pilot success criteria**

- Accuracy of imported lesson data after human review.
- Correct interpretation of stated rules and preferences.
- No rule violations in an accepted timetable.
- Number of manual corrections needed before approval.
- Time and effort reported by coordinators compared with their current workflow.
- Quality of explanations when requirements are mutually incompatible.

## Commercial positioning

**Tagline:** A better timetable starts with a conversation.

**One-line pitch:** Turn your existing school timetable and a simple conversation into a schedule that better fits your teachers, rooms, and teaching priorities.

**Short elevator pitch:** Schools shouldn’t need to wrestle with spreadsheets whenever a teacher changes availability. Timely lets timetable coordinators upload the schedule they already have, describe what should change, and review updated options with clear explanations. The school stays in control; the planning becomes easier to manage.

**Possible adoption model:** Guided pilot with individual schools; later, institutional licensing with onboarding, data access controls, and support. Pricing should be informed by customer discovery and pilot results rather than assumed in advance.

## Website concept

The accompanying `index.html` is a responsive, single-file marketing landing page. It includes:

- A concise hero and illustrative scheduling conversation.
- A three-step explanation of the proposed workflow.
- Six everyday use cases for school and academic teams.
- An interactive selector that previews example requests and responses.
- A list of customer benefits and a pilot invitation.

The example interaction on the site is **not a working scheduling engine**. It is deliberately marked as illustrative. The contact email `hello@example.com` is a placeholder that must be changed before publication.

## Future opportunities

Once a first workflow is validated, the product could expand to multi-campus timetables, substitutions, exam and room schedules, scenario comparison, institutional integrations, and more advanced scheduling preferences. Each extension should be validated with real users before being promised as a production capability.

---

**Timely** is a working name used to communicate this concept and has not been cleared for brand or trademark availability.

