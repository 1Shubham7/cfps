# Outcomes

The agent's memory across runs. One entry per submission, newest first, kept by me. The agent reads all of it before writing, so the "why" line is the part that matters: it is how the next proposal learns from this one.

Add an entry when a proposal is submitted, and update it when the result comes in. A rejection with a reason is worth more here than an acceptance without one. When the result comes, also move the file from `pending/` to `selected/` or `not-selected/`.

Format:

```
## <Conference Name Year>
- **<title>** (<format>, <track>): <accepted | rejected | waitlisted | pending | unknown>. Why: <my view, one or two lines>. File: <path in this repo>.
```

## Patterns so far

- An engineering talk with a first-person story, three named symptoms in the first sentence, and two numbers in the benefits (three months, 100+ users) was accepted at four events as a lightning talk.
- A session proposal promising four things in one slot (enable, policy, ship, alert) has not been accepted so far. Hypothesis: one point made well beats a tutorial.
- Compliance drafts were cut by hand to name areas rather than list every item, and to remove asides, self-praise and digs at other guidance. That is the house style.

## Cloud Native Summit Kerala 2026
- **Cilium Network Policy Anti-Patterns I Learned the Hard Way** (Lightning talk, Security): accepted. Why: [to fill in]. File: `selected/cilium-network-policy-anti-patterns.md`.

## KCD Gujarat 2026
- **Cilium Network Policy Anti-Patterns I Learned the Hard Way** (Lightning talk, Security): waitlisted. Why: [to fill in]. File: `selected/cilium-network-policy-anti-patterns.md`.

## Open Source SecurityCon Europe 2027 (KubeCon EU 2027 co-located)
- **Open Source Is Not Exempt: What the CRA Really Asks of Open Source Projects and Vendors** (Presentation 25 min, Regulation + Public Policy): pending, submitted 2026-10-08. Description cut to the 1,000-character limit. File: `pending/cra-open-source-is-not-exempt-securitycon.md`.

## KubeCon + CloudNativeCon Europe 2027
- **The Clock Is Already Running: Will the CRA Block Your Product from Shipping to the EU?** (Session, Security): pending. File: `pending/cra-clock-is-already-running.md`.
- **Open Source Is Not Exempt: What the CRA Really Asks of Open Source Projects and Vendors** (Session, Security): pending. File: `pending/cra-open-source-is-not-exempt.md`.

## Other events, to be filled in
- **Cilium Network Policy Anti-Patterns I Learned the Hard Way**: accepted at two further events in 2026. Events: [to fill in]. Why: [to fill in].
- **Building Your Cluster's Memory for the Worst Day: Audit -> Detect -> Alert**: not accepted so far. Events: [to fill in]. Why: [to fill in]. File: `not-selected/kubernetes-audit-logging-detect-alert.md`.

## Submitted before this repo was sorted, result to be filled in
- **New to CNCF? 5 Practical Tips to Get Involved and Make Your First Contribution** (Lightning talk): unknown. Event: KubeCon, [edition to fill in]. File: `pending/new-to-cncf-5-practical-tips.md`.
- **Why Go Keeps Winning in Cloud Native** (Session, Community, Career and Culture): unknown. Event: GopherCon, [edition to fill in]. File: `pending/why-go-keeps-winning-in-cloud-native.md`.
- **KubeAid: Stop Rebuilding the Same Kubernetes Stack for Every New Cluster** (Session): unknown. Event: KCD, [edition to fill in]. File: `pending/kubeaid-stop-rebuilding-the-same-kubernetes-stack.md`.
- **Day-2 Kubernetes: Where Most Production Clusters Break - and How KubeAid Fixes It** (Session): unknown. Event: KCD, [edition to fill in]. File: `pending/day-2-kubernetes-where-most-production-clusters-break.md`.
- **Compliance-Ready Kubernetes: Using Logs, Policies, and Git with KubeAid** (Session): unknown. Event: OpenSearchCon, [edition to fill in]. File: `pending/compliance-ready-kubernetes-logs-policies-git.md`.
