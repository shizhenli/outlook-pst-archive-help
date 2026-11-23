---
title: "PST Backup Conflicts With an Open Outlook: Diagnose the Lock"
description: "A locked or inconsistent PST backup while Outlook is running? Follow these checks to diagnose the conflict, verify a clean copy, and recover safely."
seo_title: "Fix: PST Backup Conflicts With an Open Outlook"
seo_description: "A locked or inconsistent PST backup while Outlook is running? Follow these checks to diagnose the conflict, verify a clean copy, and recover safely."
keywords:
  - "outlook pst backup while outlook open"
date: 2026-11-23T10:03:25+08:00
publishDate: 2026-11-23T10:03:25+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but Outlook was still open, and now the copy is locked or inconsistent.

## Confirm the file lock

Close Outlook completely, then open Task Manager and check for any remaining OUTLOOK.EXE process. End it if present. Navigate to the PST file, right-click it, and choose Properties. If the Read-only attribute is set, clear it. Then try copying the file to a local folder. If the copy completes without error, the lock was the cause. If it still fails, note the exact error code before continuing.

## Check the backup method

If you used a sync client or a script that copies open files, it may have captured a partial write. Compare the copied PST's size and modified time with the original. A smaller size or a timestamp that does not match the last clean Outlook close indicates an inconsistent copy. Delete that copy rather than archiving it.

## Verification test

Create a fresh folder on the same drive. With Outlook fully closed, copy the PST there and open it in Outlook via File > Open & Export > Open Outlook Data File. If all folders and recent items appear, the copy is valid. If Outlook prompts to repair or shows missing items, the copy is not trustworthy.

## Rollback and recovery

Keep the original PST untouched until the verification passes. If the verified copy fails, restore from your previous known-good backup and repeat the closed-Outlook copy. Do not overwrite the original during troubleshooting. For a controlled diagnosis of a persistent **outlook pst backup while outlook open** conflict,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
