---
title: "Outlook PST Password Prompt Blocks Access: A Controlled Fix"
description: "Stuck at the Outlook PST password prompt with no known password? Follow these checks to confirm the block, test access, and recover safely."
seo_title: "Outlook PST Password Protected: Fix a Prompt That Blocks Access"
seo_description: "Stuck at the Outlook PST password prompt with no known password? Follow these checks to confirm the block, test access, and recover safely."
keywords:
  - "outlook pst password protected"
date: 2026-11-23T11:03:33+08:00
publishDate: 2026-11-23T11:03:33+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You open your classic Outlook archive and the PST password prompt appears, but you no longer have the password or the prompt keeps returning, so access is blocked before you can diagnose anything.

## Confirm the prompt is the actual blocker

Close Outlook completely. In File Explorer, locate the PST file, right-click it, choose Properties, and check whether the Read-only attribute is set. If it is, clear it and click OK. Reopen Outlook and open the archive. If the prompt still appears, the file is **outlook pst password protected**, and the password is the blocker rather than a permissions or profile issue. If the prompt disappears, you fixed a file-attribute problem, not a password problem.

## Test whether the prompt repeats or accepts input

At the prompt, type nothing and press Enter. A correct password entry opens the archive; an incorrect or empty one returns the same dialog. If the dialog reappears immediately after you cancel, note that as a repeat loop. If it accepts a password you did not expect, stop and record it before changing anything.

## Try a safe access check

Make a copy of the PST in the same folder, then open the copy in Outlook. If the copy also prompts, the protection travels with the file. Do not delete or overwrite the original during this test.

## Rollback and recovery

Before any repair or password-removal attempt, keep the original PST untouched and work only on a copy. If a tool or procedure fails, delete the copy and return to the original; your archive remains intact.

If the prompt still blocks access after these checks,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with the exact prompt behavior and whether the copy also prompts.
