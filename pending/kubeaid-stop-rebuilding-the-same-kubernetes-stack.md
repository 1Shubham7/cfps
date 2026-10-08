---
title: "KubeAid: Stop Rebuilding the Same Kubernetes Stack for Every New Cluster"
outcome: unknown
conferences: [KCD, edition to be filled in]
format: Session
field: platform
speaker: I
---

Submitted before this repo was sorted by outcome. Result to be filled in. One of two KubeAid proposals sent to the same KCD; the other is `day-2-kubernetes-where-most-production-clusters-break.md`.

## Description

Setting up a production Kubernetes cluster means weeks configuring monitoring, GitOps, secrets management, and backups. Then you need another cluster and start over. This is one of the biggest time sinks for SRE teams. KubeAid is an open-source toolkit that solves this problem with production ready configurations for monitoring, GitOps, secrets, disaster recovery, and more - all managed through Git.

In this presentation, I will introduce KubeAid and the problem it solves, walkthrough how it provisions clusters across different platforms (AWS, Azure, Hetzner, bare metal). I will then demonstrate a live cluster setup. Later I will explain KubeAid's architecture, and share real-world use cases and success stories from companies using it in production. I will also discuss our unique open-source sustainability model. The session will conclude with a QnA to address questions from the attendees.
