<div align="center">

# Sporaa HealthHub

**Preventive, coordinated healthcare for families living apart.**

![Status](https://img.shields.io/badge/status-pilot-6B21A8)
![Stage](https://img.shields.io/badge/stage-pre--seed-6B21A8)
![Clients](https://img.shields.io/badge/clients-UK%20%7C%20US%20%7C%20Canada-6B21A8)
![Care delivery](https://img.shields.io/badge/care%20delivery-Nigeria-6B21A8)

[sporaahealthhub.com](https://www.sporaahealthhub.com/) · [jennifer@sporaahealthhub.com](mailto:jennifer@sporaahealthhub.com)

</div>

---

## The problem

Millions of people carry responsibility for the health of family members thousands of kilometres away, in another country. When something happens, they are hours behind it — calling relatives for updates, guessing at what is actually wrong, and sending money into a care system they cannot see or verify.

The result is a pattern of preventable emergencies. Chronic conditions go unmonitored between crises. Medication adherence is invisible. Nobody notices the slow decline that precedes the hospital admission, because no one is positioned to notice it.

Existing options do not solve this. Clinic directories tell you where to go, not whether anyone went. Telemedicine assumes the patient initiates contact. Neither gives the person paying and worrying any continuous visibility.

## What we are building

Sporaa is a coordination layer for care that happens in one country and is paid for and worried about in another.

- **Continuous visibility** — structured health records, visit outcomes, and medication tracking that the family abroad can actually see, rather than reconstruct from phone calls.
- **Preventive scheduling** — recurring check-ins, screenings, and follow-ups driven by the patient's actual risk profile, not by whoever remembers to book them.
- **Coordinated access** — vetted providers, home visits, diagnostics, and pharmacy fulfilment arranged through a single point of contact.
- **Predictive analytics** — surfacing the trends that precede an emergency early enough to intervene.

Our first product, the **Emerald elderly care plan**, focuses on the highest-need segment: ageing parents in Nigeria with adult children abroad.

## Current status

We are deliberately transparent about what exists today versus what is planned. Sporaa validated demand and pricing through manual operations before committing capital to engineering.

| Area | Status |
|---|---|
| Pilot operations (Lagos, Abuja) | **Live** — 9 paying subscribers on annual plans |
| Revenue | **~₦6M collected** over three months, no marketing spend |
| Waitlist | **67 prospective clients**, acquired with no marketing spend |
| Emerald elderly care plan | **Live** — requested by ~86% of the waitlist |
| Provider & partner network | **Live** — active partnerships in progress |
| Care coordination workflows | **Live**, operated manually (spreadsheets, messaging, AI-assisted tooling) |
| Patient dashboard & family portal | **In development** — see roadmap |
| Predictive analytics engine | **Planned** |
| Public API | **Planned** |

Our subscribers are based in Canada, the United States, and the United Kingdom. Care is delivered in Nigeria. Demand has come from across the English-speaking migration corridor without any marketing spend, which is why the platform is being built for multiple sending countries rather than a single route.

Our first subscribers bought annual plans in a category with no established trust, for care delivered to a relative they cannot supervise, before any platform existed. They paid upfront, at an average of roughly ₦670,000 each, without being sold to. That is the signal we are building on.

Running the pilot on manual workflows was a choice. It let us learn what families actually ask for, what providers will actually deliver, and what people will actually pay, before writing the software that automates it. The engineering roadmap below is built directly on that operational evidence.

## Engineering principles

We are currently in discussion with prospective technical partners, and platform architecture will be finalised with the team we select. The following constraints are settled, and they are the criteria we are evaluating against.

- **Cross-border data handling.** Patient data originates in Nigeria and is accessed from Canada. Residency, consent, and lawful transfer are architectural requirements, not a compliance afterthought.
- **Low-bandwidth resilience.** Caregivers and field staff operate on inconsistent mobile connectivity. Offline tolerance is a baseline expectation, not a later optimisation.
- **Role-separated access.** Patients, family members, providers, and coordinators see materially different views of the same record. Authorization is a core domain concern, not a permissions checkbox.
- **Auditability.** Every access to a health record is logged and attributable.
- **Migration-readiness.** The platform inherits a real operating dataset from the manual pilot. Data modelling starts from records that already exist, not from a blank schema.

## Roadmap

**Phase 1 — Platform foundation**
Migrate pilot operations off manual tooling. Patient records, care plans, scheduling, and coordinator workflows.

**Phase 2 — Family portal**
Family-facing dashboard for relatives abroad: visibility into visits, outcomes, medication adherence, and spend.

**Phase 3 — Intelligence layer**
Risk scoring and early-warning signals derived from the pilot dataset.

**Phase 4 — Regional expansion**
Additional Nigerian states, then Kenya and Ghana.

## Team

Sporaa is led by **Dr. Ogheneochuko Jennifer Ibe**, a medical doctor with clinical practice, health product management, and healthcare data analytics experience across Nigeria and Canada.

The team includes operations, partnerships, and design staff, supported by a three-person advisory board spanning software engineering, business strategy, and founding experience.

## Corporate structure

Sporaa operates as two legal entities under one company:

- **Sporaa HealthHub (Nigeria Operations)** — pilot operations in Lagos and Abuja.
- **Sporaa HealthHub Canada** — registered July 2026; the Canadian entity.

## Get in touch

Sporaa is not currently open to outside contributions. Repositories published here are for transparency and technical review.

For partnership, investment, or collaboration enquiries: [jennifer@sporaahealthhub.com](mailto:jennifer@sporaahealthhub.com)

## License

All rights reserved. © 2026 Sporaa HealthHub.

---

<div align="center">
<sub><a href="https://www.sporaahealthhub.com/">sporaahealthhub.com</a> — care that crosses borders.</sub>
</div>

