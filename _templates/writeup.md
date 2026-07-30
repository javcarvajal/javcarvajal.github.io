---
title: "MACHINE — Write-up"
date: 2026-07-29 18:30:00 -0600
categories: [CTF, HackTheBox]      # max 2 levels: [Parent, Child]
tags: [linux, ejpt, nmap]          # always lowercase, unlimited
description: "One-line summary: what the box taught you and the CVE or misconfig behind it."
image:
  path: /assets/img/posts/MACHINE/cover.png
  alt: "MACHINE"
toc: true
pin: false
comments: false
math: false
mermaid: false
---

## Recon

```bash
nmap -sVC -p- --min-rate 5000 -n -Pn 10.10.10.10 -oN targeted
```

## Enumeration

## Exploitation

## Privilege escalation

## Takeaways

<!--
HOW TO USE THIS FILE
  1. cp _drafts/TEMPLATE-writeup.md _posts/YYYY-MM-DD-machine-name.md
     The date in the FILENAME is mandatory — Jekyll silently ignores files
     without it. It must match the `date:` field above.
  2. mkdir -p assets/img/posts/machine-name  and drop screenshots there.
     Reference them as: ![alt](/assets/img/posts/machine-name/shot.png)
  3. Delete this comment block.

Preview drafts without publishing:  bundle exec jekyll serve --drafts
-->
