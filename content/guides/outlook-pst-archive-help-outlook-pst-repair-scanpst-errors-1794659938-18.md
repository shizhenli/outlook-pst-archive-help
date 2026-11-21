---
title: "Outlook PST Repair Scanpst Errors: When the Archive Still Won't Open"
description: "Stuck with an archive PST that won't open after ScanPST? Learn targeted checks, exact error interpretation, and a verification test to restore access safely."
seo_title: "Outlook PST Repair Scanpst Errors: Fix Archive Won't Open"
seo_description: "Stuck with an archive PST that won't open after ScanPST? Learn targeted checks, exact error interpretation, and a verification test to restore access safely."
keywords:
  - "outlook pst repair scanpst errors"
date: 2026-11-21T15:08:05+08:00
publishDate: 2026-11-21T15:08:05+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You double-click your archive folder in classic Outlook, and it refuses to open, saying the file is corrupt.

## Confirm the failure point before repairing

Close Outlook completely. Locate the PST path via File > Account Settings > Data Files, then copy the file to a local drive with free space. Do not run repair on a network path or removable drive. Right-click the copy, choose Properties, and confirm the file size is not zero and the read-only attribute is cleared. If the file is zero bytes, stop: repair cannot rebuild it, and you need backup recovery instead.

## Run ScanPST and read the result precisely

Start ScanPST.exe, browse to the copied PST, and run the scan. If it reports errors found, run the repair and repeat the scan until it reports no errors. If it reports the file is not a personal folders file, the header is damaged; stop repeating scans. If it reports access denied, close Outlook and any sync clients, then retry. These **outlook pst repair scanpst errors** often indicate the wrong file or a locked file rather than deep corruption.

## Verification test

Reopen Outlook, attempt to open the archive, and check that at least one known folder and a recent message are visible. Send a test message to yourself and confirm it appears. If the archive opens but folders are missing, do not re-repair; that is a separate folder-tree issue.

## Rollback and recovery

Keep the original PST untouched until verification passes. If repair worsens access, restore the original copy and use a backup. For persistent errors,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running further repairs.
