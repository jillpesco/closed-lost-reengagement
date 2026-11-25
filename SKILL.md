---
name: closed-lost-reengagement
description: Review closed-lost deals for verified changes that justify re-engagement. Use for win-back reviews, dormant pipeline scans, competitive displacement, or release-led follow-up.
---

# Closed-Lost Re-engagement

Review closed-lost opportunities and recommend re-engagement when a verified change after the loss gives the buyer a credible reason to reconsider. Return a ranked queue for Sales and an evidence-based brief for Marketing.

## Scope and inputs

Use the requested company and review window. Default to the trailing 12 months when the user leaves the window open. Use the supplied account list when available. Otherwise, use closed-lost CRM records within the window. If neither is available, request an export with account name or domain, opportunity identifier, closed-lost date, and recorded loss reason where available.

| Source | Use it to establish |
|---|---|
| CRM, such as Salesforce | Opportunity history, loss dates and reasons, competitors, account ownership, active opportunities, recent activity, buyer-requested timing, and contact restrictions |
| Call transcripts, such as Gong or Apollo | Buyer objections, decision criteria, stakeholders, incumbent selection, and conditions for revisiting |
| Account research, such as Apollo, ZoomInfo, or Swan | Dated company, leadership, and hiring signals and current contact roles |
| Product docs and release notes, such as GitHub | Capability availability, release dates, prerequisites, and limitations |
| Approved messaging and content library | Positioning and buyer-facing proof |
| Prior monthly scan, when supplied | New evidence, duplicate signals, and follow-up windows |

Use available connectors or supplied exports. Report unavailable sources and their effect on the review. Evaluate each loss against its own close date and reason. Return one recommendation per account and identify the opportunity it applies to.

## 1. Establish why the buyer passed

Use the CRM for the recorded close date and loss reason. Use call transcripts to identify who raised the objection, what the buyer said, and what would need to change for them to reconsider. Cite the call date or timestamp. If the sources differ, show both accounts with attribution. If a competitor won, capture who won, why, and what the buyer expected the vendor to deliver.

## 2. Verify what changed at the account

Look for a relevant leadership change in the buying group or its reporting chain, funding or M&A (including an IPO), a strategic investment, a major launch or repositioning, or a hiring surge in the function the rep originally sold into. Use only events strictly after the closed-lost date. If the event date and loss date are the same or the date is uncertain, park the signal unless a verified timestamp proves it came later. Record the event or announcement date, source, and connection to the original buying context. A detection timestamp alone is insufficient. Keep budget, willingness to reconsider, and urgency unknown unless the evidence establishes them.

If a competitor won, look in later CRM notes and call transcripts for a stalled rollout, unexpected ingestion or retention costs, coverage gaps, integration issues, or a new evaluation. Corroborate with public sources where available. Record what happened, when, and who reported it. Label buyer statements, rep observations, and third-party reports. General vendor complaints can inform a discovery question, but only verified account-specific friction qualifies as a trigger. In buyer-facing language, ask about the issue unless the buyer raised it directly with the team and it is appropriate to reference.

## 3. Check what we shipped

Search the product docs and release notes for integrations, data sources and destinations, deployment options, and relevant capability changes. For each match, record the buyer’s original requirement and call reference, what shipped, when it became available, the release source, and any prerequisites or limitations for this account. Classify it as fully addresses, partially addresses, or needs validation.

A verified release after the loss can qualify on its own if it clears an explicit blocker. For partial fits, specify what the rep needs to verify. A merged PR or recent doc edit alone is insufficient. Flag preview, roadmap, and unverified availability.

## 4. Decide who should act and when

Mark the buyer’s condition for reconsidering as met, still open, or unknown. Check for a documented renewal, rollout milestone, budget window, or requested follow-up date. Check the CRM for open opportunities, recent activity, and contact restrictions. Recommend one action:

- Reach out now.
- Reconnect at a documented milestone and include the date.
- Verify a specific missing fact first.
- Route to the owner of the active opportunity for use in that deal.
- Suppress outreach where a contact restriction applies.

Apply contact restrictions first. Route open opportunities to their owner. Otherwise honor buyer-requested timing and check for recent outreach before recommending a new touch. If CRM access is missing and ownership or contact eligibility cannot be verified, recommend verification first. If a prior scan is available, resurface the account when there is a new event, stronger evidence for an earlier signal, or an agreed follow-up window opens. Explain what changed since the last scan.

Recommend the new leader when they own the decision and include the original champion as a route in if relevant. Otherwise, recommend the original contact if they still own the issue. Flag unverified roles and reporting lines. Include the CRM owner.

## 5. Give Sales a reason to reach out and proof to share

Write one sentence that ties what changed to the original objection and a relevant product capability. Add one discovery question that tests whether the blocker still holds.

Use the company’s approved positioning when available. If it is missing, flag the messaging gap and ground the angle in verified capabilities. Pick the capability that fits the concern. For migration or lock-in concerns, verify whether the product can integrate with the buyer’s existing stack and support incremental adoption. Use the product docs to verify capabilities and use approved messaging or public docs for buyer-facing claims. Keep internal links and transcript excerpts in the rep’s brief.

Match the angle to one approved asset, such as an integration guide, technical walkthrough, migration guide, or customer example. Link it, explain why it fits, and suggest a next step. If there is no suitable asset, name the proof point Marketing should create.

## 6. Return ranked results

1. **Ranked summary table** — Include one row per qualifying account.

   | Rank | Account and opportunity | Closed-lost date | Verified trigger and date | Buyer condition | Recommended action | Timing |
   |---|---|---|---|---|---|---|
2. **Brief per account** — Recorded loss reason and buyer objection with call reference. Incumbent, why it won, and verified account-specific friction. Verified trigger or release with date and source. Re-engagement angle, discovery question, and approved asset or content gap. Best contact, route in, and CRM owner.

Rank relevant leadership changes first, then funding or M&A, major launches, and hiring surges. Rank strategic investments alongside funding when they materially change spending priorities. Give a verified product release or incumbent issue the same priority as a leadership change when it directly addresses a condition the buyer gave for revisiting. Within each group, prioritize the clearest link to the original loss and the strongest evidence.

## 7. Close the loop with Marketing

Summarize recurring objections, incumbent friction, and missing proof points for Product Marketing. Count distinct accounts and cite representative evidence. Recommend the most useful asset or enablement update and identify where Sales could use it. If the issue appears across a broader segment, suggest how Demand Gen could use the asset in a campaign.

When CRM outcomes are available, show which angles and assets were used on outreach that generated replies, meetings, or reopened opportunities. Flag missing outcome data. Usage alone does not establish that the asset drove the result. Sales owns outreach and logs outcomes. Marketing owns messaging, proof, and campaign follow-through.

End with **Park for next monthly scan**. Mark each account **No qualifying trigger found** or **Insufficient evidence to verify** and name any missing evidence.

## Worked example

A buyer said they would reconsider if they could keep their existing system and route only selected data to it. The release notes confirm support for their destination shipped after the loss. The CRM records a request to reconnect before renewal. Recommend the CRM owner follow up at the agreed time with an approved routing guide and ask whether selective routing is still the deciding requirement. If several accounts raised the same blocker and there is no approved guide, recommend that Product Marketing create one.

## Execution limits

Return recommendations only. Do not send outreach or update any system.
