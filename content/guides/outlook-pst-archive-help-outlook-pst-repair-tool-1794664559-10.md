---
title: "Archive PST Won't Open: Diagnose Before You Repair"
description: "A focused troubleshooting guide for classic Outlook users whose local archive PST will not open, with checks, result interpretation, a verification test, and rollback advice."
seo_title: "Outlook PST Repair Tool: Fix Archive Cannot Be Opened"
seo_description: "A focused troubleshooting guide for classic Outlook users whose local archive PST will not open, with checks, result interpretation, a verification test, and rollback advice."
keywords:
  - "outlook pst repair tool"
date: 2026-11-21T15:14:26+08:00
publishDate: 2026-11-21T15:14:26+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You double-click your archive folder in classic Outlook, and instead of the folder tree you get an error that the archive cannot be opened or that the file is corrupt.

## Confirm the failure is isolated to the archive

Close Outlook completely. In File Explorer, enable file name extensions and locate the archive PST. Check its size and modified date. If the size is 0 KB or the timestamp changes while Outlook is closed, stop and copy the file to a safe location before doing anything else. A zero-byte PST cannot be repaired in place; restore it from backup instead.

## Run a scan and read the result precisely

Use the Inbox Repair tool (scanpst.exe) against a copy of the archive, not the original. When the scan finishes, read the summary: if it reports minor inconsistencies and repairs them, reopen Outlook and expand the archive. If it reports that the file is not a personal folders file, or the scan stops at a percentage and never completes, the header or structure is damaged beyond a simple scan. At that point, a dedicated **outlook pst repair tool** that works on a copy is the safer next step, because it can extract recoverable items without overwriting the source.

## Verification test

After any repair attempt, open Outlook, expand the archive, and open three messages from different subfolders. Then send one test message to yourself and confirm it arrives. If the archive opens but folders are missing, the repair was partial; do not delete the original copy.

## Rollback and recovery note

Keep the untouched original PST and the repaired copy in separate folders until you have verified the contents. If the repaired file opens but loses items, return to the original and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running further repairs, so a controlled diagnosis can be completed first.
