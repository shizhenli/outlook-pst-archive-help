---
title: "Outlook Archive PST Will Not Open: When the Password Prompt Blocks Access"
description: "Stuck at the PST password prompt? Learn how to diagnose a repeating or forgotten password that prevents your Outlook archive from opening, with a safe verification test and rollback steps."
seo_title: "Outlook Archive PST Will Not Open: Fix the Repeating Password Prompt"
seo_description: "Stuck at the PST password prompt? Learn how to diagnose a repeating or forgotten password that prevents your Outlook archive from opening, with a safe verification test and rollback steps."
keywords:
  - "outlook archive pst will not open"
date: 2026-11-15T18:48:51+08:00
publishDate: 2026-11-15T18:48:51+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You double-click your archive folder in Outlook, and a password prompt appears, but the password you remember is rejected or the prompt keeps returning, leaving the archive inaccessible.

## Confirm the Prompt Behavior

First, distinguish a forgotten password from a corrupted or locked PST. Close Outlook completely. Locate the archive PST file (usually in Documents\Outlook Files or your archive path). Right-click the file, choose Properties, and note its size and date. If the file is 0 KB or missing, the issue is not the password. If it is present and sizable, proceed.

Reopen Outlook and trigger the archive again. If the prompt appears once and a wrong password gives a clear error, the password is simply unknown. If the prompt reappears immediately after you cancel, the PST may be locked by another process or damaged. Check Task Manager for lingering OUTLOOK.EXE processes and end them, then retry. A single clean prompt means the password is the blocker; a looping prompt suggests file-level trouble.

## Verification Test

Before any repair, make a copy of the PST file to a safe folder. Then try opening that copy in a new Outlook profile (Control Panel > Mail > Show Profiles > Add). If the copy also prompts repeatedly, the problem travels with the file, confirming it is not your profile. If the copy opens without a prompt, your original profile is holding a stale credential.

## Recovery and Rollback

If you cannot recall the password, do not attempt repeated guesses that may lock the file further. Use a reputable PST password recovery utility on the copy, never the original. Keep the untouched original as your rollback: if any tool fails or worsens access, restore the copy and stop. When the archive still refuses to open after these checks, the **outlook archive pst will not open** because the password layer is masking a deeper file issue, and further diagnosis is needed.

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running destructive repairs.
