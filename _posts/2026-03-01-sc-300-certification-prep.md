---
layout: post
title: "SC-300: The Plan, Revisited"
date: 2026-03-01
categories: [Certification]
tags: [SC-300, identity, azure-ad, study-guide]
---

Back in 2023, I wrote up my study plan for the SC-300. I had a home lab, a list, and good intentions. Life happened. The cert did not.

I still want this one. The SC-300 — Microsoft Identity and Access Administrator — covers Entra ID, identity governance, Conditional Access, PIM, and application access. Stuff I work with regularly, which makes the gap between knowing it and proving I know it frustrating. Time to close it.

The loop that works for me has not changed much.

**Microsoft Learn**

Start here. The learning paths map directly to the exam objectives and Microsoft updates them when the exam changes. Worth doing in order.

- [ ] [Implement an identity management solution](https://learn.microsoft.com/en-us/training/paths/implement-identity-management-solution/)
- [ ] [Implement an authentication and access management solution](https://learn.microsoft.com/en-us/training/paths/implement-authentication-access-management-solution/)
- [ ] [Implement access management for apps](https://learn.microsoft.com/en-us/training/paths/implement-access-management-for-apps/)
- [ ] [Plan and implement an identity governance strategy](https://learn.microsoft.com/en-us/training/paths/plan-implement-identity-governance-strategy/)

Take the knowledge checks seriously. They surface gaps faster than reading does.

**John Savill**

[John Savill's Technical Training](https://www.youtube.com/@NTFAQGuy) on YouTube is the best reinforcement I have found. Read the Learn content first, then watch his videos. The whiteboards make the identity flows click in a way that documentation alone does not.

- [ ] SC-300 Study Playlist
- [ ] SC-300 Exam Cram

**MeasureUp**

This is the one I cannot skip. The practice tests are aligned to actual exam style and the explanations for wrong answers are genuinely useful. Annual access on sale is the right call.

- [ ] First pass in timed exam mode — simulates real conditions
- [ ] Second pass in study mode — read every explanation, even the ones I got right
- [ ] Not moving forward until I am consistently passing each section

**Test Tenant**

The exam tests whether you can configure things, not just recognize them. Hands-on time is not optional for this one.

Microsoft offers a free 90-day renewable tenant through the [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program). Sign up with a personal Microsoft account, not a work account. The tenant comes pre-loaded with E5 licenses and sample users. Entra ID P2 is included, so everything needed for PIM and Identity Governance is right there.

Things to actually touch in the tenant:

- [ ] Build and test Conditional Access policies
- [ ] Configure PIM for directory roles
- [ ] Set up an access review
- [ ] Register an application and configure API permissions
- [ ] Stand up an entitlement management access package
- [ ] Walk through the Identity Secure Score recommendations
- [ ] Configure SSPR

The dev tenant renews automatically as long as you show active usage. Build something, break something, fix it.

**The Order**

1. Microsoft Learn — all four paths
2. John Savill cram video — fills in the big picture
3. Lab time in the test tenant — touch every major feature area
4. MeasureUp first pass — find the weak spots
5. Back to Learn and Savill for those weak spots
6. MeasureUp second pass — confirm I fixed them
7. Schedule the exam

I am not scheduling until I am ready. That was the lesson from 2023.
