---
title: "PST Password Prompt Repeats or Blocks Access: A Controlled Fix"
description: "Fix a repeating or blocking PST password prompt in classic Outlook when the password is lost, with safe checks, a verification test, and rollback steps."
seo_title: "Outlook PST Password Protected: Stop the Repeating Password Prompt"
seo_description: "Fix a repeating or blocking PST password prompt in classic Outlook when the password is lost, with safe checks, a verification test, and rollback steps."
keywords:
  - "outlook pst password protected"
date: 2026-11-28T22:14:41+08:00
publishDate: 2026-11-28T22:14:41+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Understand the prompt before you touch the file

You open classic Outlook, click your local PST archive, and a password box appears even though you no longer know the password, or it keeps reappearing after you cancel. This is the **outlook pst password protected** state, and the goal is to get past that prompt so you can diagnose the archive normally.

## Check the prompt source

First, close Outlook completely. In File Explorer, enable file name extensions and confirm the archive is a .pst, not .ost. Then reopen Outlook and click Cancel on the prompt. If the archive still appears in the folder pane but stays collapsed, the prompt is tied to that file. If Outlook closes or shows a different error, note the exact message; that changes the next step.

Next, make a copy of the PST to a separate folder before any repair attempt. This copy is your rollback point. Do not overwrite the original.

## Verification test

Open the copied PST in Outlook via File > Open & Export > Open Outlook Data File. If the same password prompt appears on the copy, the protection is inside the file, not a profile glitch. If the copy opens without a prompt, the original may be locked or corrupted rather than password-protected, and you should treat it as a repair case instead.

## Recovery note

If a repair tool or password-removal step fails, delete the working copy and return to the untouched original. Never run repeated repair attempts on the only copy. When the prompt still blocks diagnosis,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with the exact prompt text and whether the copy behaved differently.

## Expected result

After these checks you should know whether the prompt is genuine protection or a lock/corruption symptom, and you can proceed with the correct fix without risking the archive.
