---
title: "Outlook PST Password Prompt Blocks Access: A Targeted Fix"
description: "Stuck at a repeating Outlook PST password prompt? Follow these targeted checks to diagnose and restore access to your password-protected PST archive."
seo_title: "Outlook PST Password Prompt Blocks Access: Targeted Fix"
seo_description: "Stuck at a repeating Outlook PST password prompt? Follow these targeted checks to diagnose and restore access to your password-protected PST archive."
keywords:
  - "outlook pst password protected"
date: 2026-11-16T11:03:19+08:00
publishDate: 2026-11-16T11:03:19+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You open your classic Outlook archive and the PST password prompt appears, but the password you remember is rejected or the prompt keeps looping, blocking access before you can diagnose the file.

## Confirm the Prompt Type and File State

First, identify which PST is prompting. In Outlook, go to File > Account Settings > Data Files and note the full path of the archive. Close Outlook completely. In File Explorer, right-click the PST, choose Properties, and check if the Read-only attribute is set. If it is, clear it and click Apply. A read-only PST can cause the password prompt to repeat because Outlook cannot write the unlock state. Also confirm the file is local, not on a network share, since network latency can make the prompt loop.

## Test the Password in Isolation

Do not keep guessing inside Outlook. Use a controlled test: make a copy of the PST to a local folder, then try opening the copy in Outlook via File > Open & Export > Open Outlook Data File. If the copy prompts once and then opens with a known password, the original file has a lock or permission issue, not a password problem. If the copy also rejects the password, the PST is genuinely **outlook pst password protected** with a credential you no longer have.

## Verification and Rollback

After clearing read-only or moving the file locally, reopen Outlook and access the archive. Success means the prompt appears once, accepts the password, and the folder tree loads. If the prompt still repeats, stop and preserve the original PST before any further changes. Keep a backup copy; do not delete or overwrite the original until access is restored. For persistent password rejection,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) to diagnose the protected file safely.
