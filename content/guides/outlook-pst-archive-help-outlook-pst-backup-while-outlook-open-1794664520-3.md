---
title: "Outlook PST Backup While Outlook Is Open: Resolve the Lock Conflict"
description: "A locked or inconsistent PST backup while Outlook is running? Follow these checks to confirm the conflict, test a safe copy, and recover without data loss."
seo_title: "Outlook PST Backup While Outlook Open: Fix Lock Conflicts"
seo_description: "A locked or inconsistent PST backup while Outlook is running? Follow these checks to confirm the conflict, test a safe copy, and recover without data loss."
keywords:
  - "outlook pst backup while outlook open"
date: 2026-11-21T15:11:10+08:00
publishDate: 2026-11-21T15:11:10+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but Outlook was still open, and now the copy is locked or inconsistent. This is a common conflict, and it is fixable with a few controlled steps.

## Confirm the conflict

First, close Outlook completely. Check Task Manager for any lingering OUTLOOK.EXE process and end it. Then try copying the PST file again. If the copy succeeds with Outlook closed, the conflict is confirmed: Outlook had an exclusive lock on the file.

Next, verify the PST's integrity. With Outlook closed, run the Inbox Repair Tool (scanpst.exe) on the original file. A clean scan means the source is healthy; errors mean you should repair before backing up.

## Test a safe backup method

Reopen Outlook and use File > Open & Export > Import/Export to export the archive to a new PST. This creates a consistent copy even while Outlook runs, because Outlook manages the write operation. Compare the exported file size and folder count to the original. A matching structure indicates success.

If you must copy the raw file, schedule it during Outlook's closed hours or use a volume shadow copy tool. Avoid direct copy while Outlook is open, as this is the root of the **outlook pst backup while outlook open** conflict.

## Verify and recover

After any backup, open the copy in Outlook via File > Open & Export > Open Outlook Data File. Confirm key folders and recent emails are present. If the copy fails to open, delete it and restore from your last known-good backup. Keep the original PST untouched until verification passes.

If the conflict persists or the PST shows errors,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
