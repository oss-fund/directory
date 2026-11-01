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
lastmod: 2026-10-27T00:00:00+00:00
link: "https://red.anthropic.com/oss-scanner/"
verified: true
verified_on: 2026-10-27
checked_by: "OSS.Fund editorial review"
evidence_urls:
- "https://red.anthropic.com/oss-scanner/"
- "https://red.anthropic.com/oss-scanner/terms/"
- "https://www.anthropic.com/legal/consumer-terms"
- "https://github.com/anthropics/oss-scanner"
- "https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source"
next_recheck_on: 2027-01-27
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

**Eligibility and enrollment.** The program targets established projects with critical impact on infrastructure and user security. Anthropic considers requests case by case, weighing factors such as remote-attack exposure, project dependencies, activity, license, and usage. New projects and forks generally do not qualify unless they independently meet the criteria. Core maintainers or people authorized by the lead maintainer enroll by opening a [pull request to the enrollment repository](https://github.com/anthropics/oss-scanner), providing a project configuration, Dockerfile, and primary contact; a threat model is optional. An employee enrolling a project in their formal role also needs the organization’s permission. Anthropic manually reviews enrollment, verifies maintainer and security-contact authority, and checks scanner scope. Contact email addresses in the public enrollment repository are visible publicly, so use an address intended for publication.

**Tradeoffs.** Vulnerability reports are model-generated without human review and may be incomplete or incorrect; maintainers are responsible for checking reports and proposed patches. The agreement designates reports as Anthropic confidential material. Separately, it requires reasonable steps to keep them confidential and secure until the vulnerability is fixed or publicly disclosed; it does not say that the confidential-material designation ends then. Reports may be shared only with authorized project maintainers and used only to assess and fix the project. If Anthropic manually validates a report under its coordinated disclosure process, it may disclose the vulnerability starting 90 days after notifying the participant that a human has validated that report. The agreement provides the service and reports as-is. Scans recur, but the documentation promises no fixed schedule. Projects can pause or withdraw through the enrollment repository.

See the [official FAQ](https://red.anthropic.com/oss-scanner/), [terms](https://red.anthropic.com/oss-scanner/terms/), and [launch announcement](https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source). Anthropic may approve or end enrollment at its discretion. OSS Scanner is separate from Claude for Open Source's subscription program.
