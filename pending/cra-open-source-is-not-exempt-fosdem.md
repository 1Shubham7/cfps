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
