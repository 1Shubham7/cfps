---
title: "Why Go Keeps Winning in Cloud Native"
outcome: unknown
conferences: [GopherCon, edition to be filled in]
format: Session
track: Community, Career and Culture
field: community
speaker: I
---

Submitted before this repo was sorted by outcome. Result to be filled in.

## Abstract

Most of the cloud native landscape is Go - but not because Go is fast. Docker chose it to target Linux, not a runtime, and so strangers could read the source. This talk covers the five properties that made it stick, where Go genuinely loses to Rust, and why the Go runtime is now changing to match how we deploy it - and new domains keep choosing it.

## Detailed Description

Almost everything we run in production is Go. The usual explanations - speed, goroutines - aren't the real reason. I'll start with Docker's actual reasoning, then work through five properties that turned an early accident into a durable fit: static binaries becoming the container image, goroutines becoming the reconcile loop, interfaces becoming CRI/CNI/CSI, a stdlib built for operability, and a compatibility promise that lets a thousand repos upgrade together. Then the honest part: the workload where Go loses to Rust, and why Cilium pushed its datapath into the kernel instead of rewriting. And how the Go runtime is now being changed in response to how we deploy it, and why when a new domain pick a language, they're still picking Go.

## Why this talk matters

We say "Go won cloud native." Almost nobody can say why, and I couldn't either until I went looking. The answer turned out to be more interesting than speed or goroutines and that is what I want to share with this talk. Why me: I've been in the cloud native ecosystem for four years and contributing to CNCF projects for three. I work as an SRE running cloud native OSS in production for real customers. I've spend time reading code for such projects and I've been paged by it - that's the perspective I want to bring to the room.
