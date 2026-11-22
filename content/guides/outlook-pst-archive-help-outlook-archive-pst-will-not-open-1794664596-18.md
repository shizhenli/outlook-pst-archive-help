---
title: "Outlook Archive PST Will Not Open: Bypass a Blocking or Repeating Password Prompt"
description: "Stuck at a PST password prompt you cannot clear? Follow these targeted checks to diagnose and bypass a blocking or repeating password dialog in classic Outlook."
seo_title: "Outlook Archive PST Will Not Open: Fix a Blocking Password Prompt"
seo_description: "Stuck at a PST password prompt you cannot clear? Follow these targeted checks to diagnose and bypass a blocking or repeating password dialog in classic Outlook."
keywords:
  - "outlook archive pst will not open"
date: 2026-11-22T12:03:43+08:00
publishDate: 2026-11-22T12:03:43+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You open your archive folder and Outlook immediately asks for a PST password you no longer have, or the same prompt keeps returning even after you cancel it.

## Confirm the prompt source before changing anything

First, close the password dialog with Cancel. If Outlook continues loading and the archive appears, the prompt is a leftover credential request, not a locked file. If the archive stays unavailable, note the exact dialog title and whether it reappears immediately. A prompt that returns after every Cancel points to a stored password entry or a damaged PST header, not a forgotten password.

## Check for a saved password in Windows Credential Manager

Open Credential Manager from the Start menu and review Windows Credentials. Look for entries containing Outlook or the PST filename. Remove only the matching entry, then restart Outlook and open the archive again. If the prompt stops and the folder tree loads, the stored credential was the cause. If the prompt still blocks access, proceed to the next check.

## Test the PST outside the profile

Create a new Outlook profile and add the archive PST there. If the password prompt does not appear in the new profile, your original profile holds the bad credential and can be rebuilt. If the prompt persists, the PST itself is requesting the password, which means **outlook archive pst will not open** until the file is repaired or the password is recovered.

## Verification test

Reopen the original profile and the archive. Success means the folder tree appears without a password dialog. If the dialog returns, stop retrying and preserve the PST before any repair attempt.

## Rollback note

Before repairing, copy the PST to a separate drive. If a repair tool alters the file, restore the copy and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) rather than overwriting the original.
