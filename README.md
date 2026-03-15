# OSS.Fund Directory Data

Contains the listing data for [OSS.Fund](https://oss.fund/), including platforms, programs, and services related to funding, revenue, and resources for open source maintainers and contributors.

If you want to update an existing listing or add a new one, open a pull request in this repository.

## Update an existing entry

This is a crowdsourced directory maintained by contributors.

To update an existing entry, edit the relevant file in the [posts](./posts) directory and submit a pull request.

## Add a new entry

If your platform, program, or service helps open source maintainers or contributors with funding, revenue, or project support, you can add it to [OSS.Fund](https://oss.fund/).

To add a new entry, create a new Markdown file in the `posts` directory with the required metadata and content, and include a logo image if applicable.

Example:

```markdown
---
title: "Patreon"
date: 2020-06-20T08:20:00+02:00
type: post
categories:
  - Donations
tags:
  - Live
  - Creative works
  - Publishing
  - Education
draft: false
images:
  - /images/patreon.jpg
comments: true
lastmod: 2020-06-20T08:20:00+02:00
link: "https://patreon.com"
twitter: patreon
description: "Empowers membership businesses for creators through regular donations."
organization: "Corporation"
monetization: "Regular donations"
technology: "Closed source"
status: "Live"
activity: 3000000
activity_text: "More than 3 million patrons support more than 100,000 creators"
payment_services: "PayPal, credit card"
fee: "5%-12%"
fee_text: "Lite 5%, Pro 8%, Premium 12%"
---
Empowers membership businesses for creators through regular donations.<!--more-->
````

## License

This repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to use the content with attribution to [OSS.Fund](https://oss.fund/).
