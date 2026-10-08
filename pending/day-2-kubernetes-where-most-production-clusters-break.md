---
title: "Day-2 Kubernetes: Where Most Production Clusters Break - and How KubeAid Fixes It"
outcome: unknown
conferences: [KCD, edition to be filled in]
format: Session
field: platform
speaker: we
---

Submitted before this repo was sorted by outcome. Result to be filled in. One of two KubeAid proposals sent to the same KCD; the other is `kubeaid-stop-rebuilding-the-same-kubernetes-stack.md`.

## Description

Provisioning a Kubernetes cluster is only the beginning. Most production incidents don’t happen on day one - they happen on day two and beyond, when monitoring alerts don’t fire, secrets need rotation, backups fail silently, upgrades introduce breaking changes, and clusters slowly drift out of control.

This talk will focus on the real challenges of Kubernetes day-2 operations drawing directly from experience building and operating KubeAid in real environments by KubeAid Creators, we will walk through the most common operational pain points SRE and platform teams face after clusters go live.

Using KubeAid we’ll explore how day-2 concerns such as monitoring, GitOps, secrets management, backups, and disaster recovery can be standardized and managed entirely through Git. We will talk about how KubeAid applies opinionated, production-tested defaults to reduce operational overhead. Throughout the session, we’ll share practical operational tips and lessons learned from creating and maintaining KubeAid - what worked, what failed, and what actually matters when running Kubernetes in production. The session will conclude with a QnA to discuss questions from the audience.
