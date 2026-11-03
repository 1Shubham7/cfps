---
title: "Open Source Is Not Exempt: What the CRA Really Asks of Open Source Projects and Vendors"
outcome: pending
conferences: [FOSDEM 2027]
format: Devroom talk (length to confirm against the devroom call)
submitted: 2026-11-02
track: Beyond the CRA - Building Secure and Resilient Open Source
field: open source
speaker: we
---

FOSDEM 2027 version of `pending/cra-open-source-is-not-exempt.md`, written by dodo on 2026-11-01 for the "Beyond the CRA - Building Secure and Resilient Open Source" devroom (pretalx track 831). FOSDEM's form has a title, a track, a markdown abstract and private submission notes; there is no "benefits" field, so the benefits text is folded into the notes. FOSDEM asks for links to every project mentioned, so KubeAid and the tools are linked. The devroom's own call text was not published at the time of writing; the track was open in the pretalx dropdown. Submitted by Shubham through pretalx on 2026-11-02 with the text below unchanged apart from small edits.

## Proposal title

Open Source Is Not Exempt: What the CRA Really Asks of Open Source Projects and Vendors

## Track

Beyond the CRA - Building Secure and Resilient Open Source

## Abstract

The EU Cyber Resilience Act ([Regulation (EU) 2024/2847](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)) is the first EU-wide law to put binding cybersecurity requirements on software and hardware products across every sector, and the first to give open source its own legal role: the open source steward. From 11 December 2027 it decides which products may be placed on the EU market at all, and its reach goes well beyond Europe, because any vendor selling there must account for every component in its product, wherever that code was written.

For most of its history, security in open source has run on goodwill. That is changing. As governments start writing security into law, a security policy, a way to report vulnerabilities and timely fixes stop being good practice and become something regulators, customers and downstream vendors expect to see. This matters to everyone in the ecosystem: users deciding which projects they can depend on, contributors, project owners, and the enterprises behind open source projects.

In this talk we will explain what the CRA actually is and the positions an open source project can be in: out of scope, open source steward, or manufacturer, with a simple test to tell them apart. We will cover what an open source project is expected to do to comply, what vendors building on open source will be required to do, and what they will start asking project maintainers for. We will also talk about where open source security is heading as laws like the CRA come into force. We maintain open source projects ourselves, including [KubeAid](https://github.com/Obmondo/KubeAid), an open source Kubernetes platform, and at work we help companies comply with standards such as ISO 27001, the CRA, GDPR and NIS2. From that, we will share a practical checklist drawn from applying all 71 articles of the regulation to real projects, using only open source tools such as [Trivy](https://github.com/aquasecurity/trivy), [Falco](https://github.com/falcosecurity/falco) and [CISO Assistant](https://github.com/intuitem/ciso-assistant-community).

This talk will be a complete map of what the Cyber Resilience Act means for open source, and of where open source security is headed as a result. Attendees will leave with a clear understanding of what the CRA is, which role their project falls into, exactly what that role requires and by when, and a concrete checklist they can start working through the next morning.

## Submission notes (private, for the organisers)

Why this talk, in this devroom: open source is at a turning point. For years its security has been a matter of best practice. The CRA, in force since December 2024 and applying in full from 11 December 2027, turns that into a legal matter, with a named role for the organisations behind open source, dated obligations, and real consequences for the vendors who ship it. Most of the engineers who actually maintain this code have not heard that this is happening. Our aim is to give the room, in one session, which role a project falls into, the exact duties and dates for each role, what downstream vendors will now ask of maintainers, and a short checklist any project can act on. The talk also shows how the new duties on vendors can work in the ecosystem's favour, turning vulnerability handling into a shared responsibility between maintainers and the companies that depend on them, instead of a burden carried by volunteers. Everything in it comes from applying the regulation to open source projects we maintain ourselves.

Length: we can fit 25 to 30 minutes plus questions, or shorten to a 20 minute slot if the devroom schedule needs it.

Speaker: Shubham Singh Mahar, Site Reliability Engineer at Obmondo, a Danish managed service provider, maintainer on KubeAid, CNCF contributor (Kyverno, KubeEdge, kgateway, ArgoCD), Certified Kubernetes Administrator. Previous talks: KubeCon 2024, Open Source Summit 2025, Cloud Native Summit, IndiaFOSS. Recordings: KubeEdge deep dive https://www.youtube.com/watch?v=KOqvDqtmIpA and Cilium Network Policy Anti-Patterns https://www.youtube.com/watch?v=WYleGWU5exw

## Speaker Biography

Shubham is a Site Reliability Engineer by day and a Cloud Native Developer by night. He is a Certified Kubernetes Administrator (CKA) and a graduated LFX Mentee with CNCF KubeEdge. He has been contributing to CNCF projects for over three years and has been working with startups for over three years. Over the last two years he has helped multiple organisations build and audit infra against global security and compliance standards.

## Form choices

- Track: Beyond the CRA - Building Secure and Resilient Open Source
- Software license(s): KubeAid: AGPL-3.0. Trivy: Apache-2.0. Falco: Apache-2.0. CISO Assistant: AGPL-3.0.
- Recording release (CC-BY / CC-BY-SA) and Code of Conduct: agreed by Shubham
- Session image, additional speaker, matrix id, extra contact: left empty
