---
title: "Anthropic OSS Scanner"
date: 2026-10-08T00:00:00+00:00
type: post
categories:
- Infrastructure
pillar: "Operational Support"
tags:
- OSS-specific
- Security
- Developer tooling
- AI
draft: false
images:
- "https://github.com/anthropics.png"
lastmod: 2026-10-26T00:00:00+00:00
link: "https://red.anthropic.com/oss-scanner/"
verified: true
verified_on: 2026-10-26
checked_by: "OSS.Fund editorial review"
evidence_urls:
- "https://red.anthropic.com/oss-scanner/"
- "https://github.com/anthropics/oss-scanner"
- "https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source"
next_recheck_on: 2027-01-26
description: "Anthropic OSS Scanner offers free recurring vulnerability scans for eligible established open source projects. Reports are model-generated and require maintainer review."
organization: "Corporation"
monetization: "Anthropic-funded security scanning for accepted open source projects"
technology: "AI-assisted vulnerability scanning with reproduction details and proposed patches where available"
open_source_status: "Hosted scanning service using Anthropic models; public enrollment repository licensed under Apache-2.0"
status: "Live"
activity_text: "Launched on 8 October 2026 and accepts enrollment pull requests. The cited documentation does not state a program-wide enrollment total."
fee: "Free for accepted projects"
fee_text: "Anthropic covers scanning costs for accepted projects. Maintainers provide a build environment and handle validation and remediation of findings."
best_for:
  goals: ["cover-costs"]
  project_types: ["library", "tool", "application", "infrastructure"]
  community_size: ["established", "large"]
  team: ["solo", "small-team", "organization"]
  effort: ["some"]
finder_pitch: "Free recurring security scans for established, security-critical OSS projects with capacity to triage findings. Reports arrive without human review; acceptance is case by case."
---

Anthropic OSS Scanner provides free, opt-in vulnerability scans for accepted open source projects. Reports include reproduction details and proposed patches where available. This is security support rather than direct maintainer funding.<!--more-->

**Eligibility and enrollment.** The program targets established projects important to infrastructure and user security. New projects and forks generally do not qualify unless they independently meet the criteria. Core maintainers apply through a [pull request to the enrollment repository](https://github.com/anthropics/oss-scanner), providing project configuration, a Dockerfile, and a security contact. A threat model is optional.

**Tradeoffs.** Findings are model-generated without human review and may be incorrect. Maintainers need capacity to validate and fix reports. Scans recur, but the documentation promises no fixed schedule. Projects can pause or withdraw through the enrollment repository.

See the [official FAQ](https://red.anthropic.com/oss-scanner/) for current eligibility and operating terms and the [launch announcement](https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source) for background. OSS Scanner is separate from Claude for Open Source's subscription program.
