# Citi India Hackathon 2026 — Ada Lovelace: live briefing notes

Captured from seven user-provided meeting screenshots on **2026-10-13**.

> These notes summarize the visible slides, not the meeting audio or a complete rulebook. The schedule and contact slides explicitly confirm the **2026 edition**. Requirements below come from the current briefing screenshots and take precedence over historical examples in [the web research](./citi_ada_lovelace_2026_research.md).

## 1. Actual challenge

**Reimagining Education & Economic Empowerment for Rural India**

### Problem

Education does not always translate into relevant skills, practical capabilities, or economic opportunity for rural learners. Access to quality learning, career guidance, professional exposure, vocational pathways, and opportunities to apply learning can be limited. Formal education, vocational/informal learning, mentorship, apprenticeships, and work often exist in disconnected ecosystems.

The brief proposes using AI, local-language voice interaction, and real data to connect those ecosystems.

### Vision and intended users

An inclusive, accessible, future-ready education ecosystem in which rural students know:

- What they are good at.
- How to develop those strengths.
- How to monetize them.
- Who can connect them to opportunities.

Users: **students in rural India and village teachers/facilitators**. The overview slide describes students as “Standard 9th to Graduation ?”; the question mark is in the slide, so the precise age/education range needs confirmation.

## 2. Expected solution

The brief calls for **a working prototype of an AI-powered learning-to-livelihood platform** demonstrating the potential to achieve these objectives.

**This describes the overall product expectation, not necessarily the Round 1 submission.** The separate Round 1 slide specifies a proposal format.

### Core objectives

| Objective | Visible brief |
| --- | --- |
| **Discover** | Local-language voice/text conversation builds a profile of interests, skills, and goals. AI suggests potential careers, including STEM, non-STEM, and vocational options. |
| **Learn** | Personalized learning pathways explain what to learn next and relevant competitive exams to prepare for. Do not restrict recommendations to a few popular careers. |
| **Opportunity / Earn** | Match learners to scholarships, government schemes, apprenticeships, mentors, and employers; the overview also mentions internships and jobs. |

### “Go deeper” objectives in the detailed table

- **Connect & Earn:** mentor, corporate, and NGO onboarding; apprentice/internship listings, where to find them, and a way to apply.
- **Facilitator enablement:** teachers/facilitators can identify talent and recommend students for opportunities.
- **Sustainability:** teachers/facilitators can build and run their own training modules, offering them free, paid per module, or by subscription.

The detailed table labels these separately from “Core.” Confirm how much of this must be implemented at each stage; do not silently treat them as either mandatory in full or optional.

## 3. Technical requirements shown

### Must-include summary

- Local-language **voice input and output**.
- A simple interface for low-literacy users.
- Operation on **low-end Android phones**.
- Offline/low-bandwidth operation, with synchronization when connected.
- **Facilitator mode:** one teacher can help many students.
- AI grounded in real data.
- Accessibility and extensibility.

### Five requirement areas

| Area | Slide requirement |
| --- | --- |
| **Open-source architecture & extensibility** | Built using an open-source architecture to support adoption, replication, and community contributions. Extendable to new languages, occupations, mentors, employers, and workforce ecosystem partners. |
| **Meaningful intelligence** | Purposeful AI addressing real user needs. An LLM with a knowledge base of schemes, scholarships, exams, courses, and apprenticeships; use for profiling, career matching, eligibility checks, and pathway generation. |
| **Multilingual & voice-enabled access** | Multiple regional languages, voice interactions, speech-to-text, and text-to-speech. |
| **Low-bandwidth & offline-first design** | Key functionality works offline in low-connectivity environments, with synchronization when connectivity returns. |
| **APIs & interoperability** | Standards-based APIs for integration with colleges, employers, NGOs, and government systems. |

### Additional technical stack / evaluation matrix slide

The later slide titled **“Technical Requirements & Evaluation Matrix”** lists:

| Category | Technologies/standards named on the slide |
| --- | --- |
| Open Banking & Secure Connectivity | Open APIs, OAuth2 authentication, ISO 20022 message standards. |
| NLP & Machine Learning Models | Open-source LLMs, embeddings, predictive analytics engines. |
| Data Processing & Visualization | Pandas, NumPy, Scikit-learn, interactive chart libraries. |
| Frontend Interface | React.js, Next.js, modern responsive UI frameworks. |
| Privacy & Compliance | GDPR, CCPA, India DPDP Act standards, and data governance. |

**Applicability needs confirmation:** this slide includes banking-specific standards, while the stated challenge is rural education. Record them as shown, but ask whether they are mandatory for this problem, examples, or general event guidance. Do not silently discard them or assume every named library is compulsory. The slide's references to privacy laws are organizer wording, not a legal determination that every law applies to every implementation.

**Still not established:** number of languages, Android-native vs web app, approved models/API providers, whether AI inference itself must work offline, and whether live third-party integrations are required. The matrix explicitly mentions open-source LLMs; confirm whether hosted open-source models or proprietary services are permitted and what repository license/publication is expected.

## 4. Judging rubric

| Criterion | Weight |
| --- | ---: |
| Innovation & Originality | **25%** |
| Technical Feasibility & Architecture | **20%** |
| Usability & Scalability | **20%** |
| Ability to Monetize the Product | **15%** |
| Customer Impact & UX | **20%** |
| **Total** | **100%** |

These weights are visible in the overview, detailed table, and later evaluation matrix. The matrix labels the 15% category **“Business Value & Monetization”** rather than “Ability to Monetize the Product”; the weight is unchanged. These replace the incomplete historical judging headings for preparation for this brief.

## 5. Round 1 — project proposal format

Slide heading: **“Round 1 - Project Proposal Format - Lean Canvas.”**

Include **college name, team name, and team members**, followed by:

| Field | What the slide asks for |
| --- | --- |
| Problem | Your top 1–3 problems. |
| Existing Alternatives | How those problems are solved today. |
| Solution | A possible solution for each problem. |
| Key Metrics | Key numbers indicating how the business is doing. |
| Unique Value Proposition | A single, clear, compelling message explaining why you are different. |
| High-Level Concept | An “X for Y” analogy; the slide uses “YouTube = Flickr for videos.” |
| Unfair Advantage | Something that cannot easily be bought or copied. |
| Channels | Your path to customers, inbound or outbound. |
| Customer Segments | Target customers and users. |

**Confirmed:** the shown Round 1 format is a Lean Canvas proposal.

**Still unknown:** submission portal, file type, page/slide limit, whether supporting architecture/demo/code is also required, and presentation requirements. The schedule gives dates but has a deadline discrepancy recorded below. Do not invent extra Lean Canvas fields or assume this slide is the entire submission instruction.

## 6. Team structure and 2026 schedule

**Team structure: 5 participants, including at least 1 woman participant.** This is the wording on the schedule slide, not “up to 5.” Other eligibility rules are not shown.

All clock times below are **IST**; all dates are **2026**.

| Event | Start | End | Time / duration shown | Format / communication |
| --- | --- | --- | --- | --- |
| Launch | 13 October | 13 October | 11:30–12:30 PM IST, as written on slide | Virtual |
| Round 1 — Project Proposal | 13 October | 18 October | By 6:00 PM | Virtual |
| Project Proposal Submissions | 19 October | 19 October | By 6:00 PM | Virtual |
| Round 1 winners announcement | 2 November | 2 November | 8:00 PM | Email to the college |
| Round 2 — PoC | 16 November | 18 November | 3 days | Virtual |
| PoC demos | 20 November | 20 November | 11:00–2:00 PM IST, as written on slide | Virtual |
| Round 2 winners announcement | 23 November | 23 November | 3:00 PM | Email to the college |
| Final prototype development | 23 November | 29 November | Slide says “5 Days” | Virtual |
| Finale events | 30 November | 30 November | 12:00–4:00 PM | In person |
| Final winners announcement | 30 November | 30 November | 3:30 PM | Virtual / in person |

### Schedule discrepancies — do not silently resolve

- **Round 1 ends 18 October at 6 PM, but the separate proposal-submission row says 19 October at 6 PM.** Confirm the actual deadline. As a conservative planning choice, have the proposal ready by **18 October, 6 PM IST**; this is our recommendation, not an organizer clarification.
- **23–29 November spans seven calendar dates**, although the final-development row says “5 Days.” Confirm the intended working window.
- The 11:30–12:30 and 11:00–2:00 ranges use a single “PM” label. They appear to mean late-morning-to-afternoon slots; verify exact start times in invitations.
- The finale is explicitly **in person**. Venue, travel arrangements, and who must attend are not shown.

## 7. Wording that needs clarification

1. **Offline scope:** the brief explicitly requires offline-first functionality but also lists a “village with no internet connectivity” as out of scope. It may distinguish intermittent connectivity from permanently disconnected settings, but that is an interpretation—not confirmed. Ask what must work offline and whether periodic internet access is assumed.
2. **Stage-specific scope:** what must be demonstrated in Round 1 versus later rounds? How are “Core” and “Go Deeper” assessed?
3. **Open-source requirement:** does it require publishing all source code under a particular license, and are hosted/proprietary AI APIs allowed?
4. **Integration expectations:** are documented APIs and representative data sufficient, or must actual external systems be connected?
5. **Learner range:** confirm the intended school/college ages and supported languages.
6. **Technical matrix applicability:** are the banking standards and named technologies mandatory for the rural-education challenge?
7. **Schedule:** resolve the 18/19 October deadline discrepancy and the final-development duration.

## 8. Immediate approach — our interpretation, not an organizer instruction

The project is **not just a generic education chatbot**. The brief connects learner discovery, learning pathways, economic opportunities, facilitator support, and sustainability under rural-access constraints.

For now, prioritize the **Round 1 proposal**: choose 1–3 concrete user problems, explain a connected solution, identify users versus paying customers, state the distinctive value, and define measurable outcomes. Do not select a large technology stack before confirming the submission and offline requirements.

Possible later demo storyline: a learner describes interests in a regional language → gets an explainable profile and learning pathway → finds a relevant, source-backed opportunity → a facilitator supports several learners. This is a suggested coherent demonstration, **not permission to omit the remaining brief**.

### Still worth capturing from the meeting

- [ ] Clarified proposal deadline: 18 or 19 October? Submission portal and file/template requirements.
- [x] Team size/composition: 5 participants, including at least 1 woman.
- [ ] Remaining participant eligibility rules.
- [x] Schedule and round names captured; discrepancies remain open.
- [ ] Detailed round-by-round deliverables and scope answers.
- [ ] Attendance requirement and recording/slides location.
- [ ] Finale venue and travel arrangements.

## 9. Contacts and support

The contact slide identifies the support channel as the **Early Career India Team**.

| Contact | Email as shown |
| --- | --- |
| Mohini Saluja | `mohini.saluja@citi.com` |
| Vinodhini Sivaraman | `vinodhini.sivaraman@citi.com` |
| Krati Srivastava | **Malformed on slide:** `krati.srivastavati.com`; obtain the correct address before using. |
| Isha Thaman | `isha.thaman@citi.com` |
| Annanda Manokaran | `annanda.kumar.manokaran@citi.com` |
| Balaji Ranjan | `balaji.ranjan@citi.com` |
| Swetha.K | `swetha.k@citi.com` |

Support notes on the slide:

- Dedicated mentor support **from Round 2**.
- Senior and seasoned mentors.
- Email coordinators for queries.

No messages have been sent. Email addresses are transcribed from the supplied image, not independently verified. The contact slide footer explicitly reads **“Citi India Hackathon 2026 | Ada Lovelace Day.”**

## 10. Preserved screenshots

- [Problem overview and judging](./assets/briefing/problem_overview.png)
- [Technical requirements](./assets/briefing/technical_requirements.png)
- [Detailed problem statement table](./assets/briefing/problem_statement_table.png)
- [Round 1 Lean Canvas format](./assets/briefing/round_1_lean_canvas.png)
- [Team structure and schedule](./assets/briefing/schedule.png)
- [Technical stack and evaluation matrix](./assets/briefing/technical_evaluation_matrix.png)
- [Contacts and support](./assets/briefing/contacts_and_support.png)

The detailed table is low resolution. It was read alongside the larger overview and technical slides; obtain the original deck for exact wording. Images are retained locally as supplied; the Zoom captures also contain participant video/UI.
