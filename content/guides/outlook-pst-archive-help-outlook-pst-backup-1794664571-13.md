---
title: "PST Backup Conflicts With an Open Outlook: Resolve the Locked Copy"
description: "A backup copy is locked or inconsistent while classic Outlook is running. Diagnose the open-file conflict, verify a clean copy, and recover safely."
seo_title: "Outlook PST Backup Locked or Inconsistent While Outlook Runs — Fix"
seo_description: "A backup copy is locked or inconsistent while classic Outlook is running. Diagnose the open-file conflict, verify a clean copy, and recover safely."
keywords:
  - "outlook pst backup"
date: 2026-11-21T15:14:26+08:00
publishDate: 2026-11-21T15:14:26+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but the copy is locked or inconsistent because Outlook still has the file open.

## Understand the conflict

Outlook keeps the PST open and writes to it continuously. A file-copy tool that reaches the PST while Outlook is running can produce a locked, partial, or inconsistent copy. This is a timing and file-lock problem, not proof that the archive is damaged. Do not delete the original PST or overwrite it with the suspect copy.

## Run these checks

1. In Outlook, check File > Account Settings > Data Files and note the exact path of the PST you are backing up. Confirm the backup tool is pointed at that same file, not at a similarly named one.
2. Close Outlook completely. Open Task Manager, find any remaining outlook.exe process, and end it. Then try copying the PST again.
3. If the copy succeeds only when Outlook is closed, the conflict is confirmed: the backup ran against an open file. If it still fails with Outlook closed, check free disk space and whether the destination folder is read-only or on a disconnected drive.
4. Compare file sizes and timestamps between the original and the copy. A copy that is smaller or has a different timestamp than the source after a clean close is not trustworthy.

## Verify the copy

With Outlook still closed, open the copied PST in Outlook via File > Open & Export > Open Outlook Data File. Expand the main folders and confirm recent items are present. If the copy opens and shows current mail, the **outlook pst backup** is usable. If it prompts for repair or shows missing items, discard it and repeat the copy from the original.

## Roll back safely

Keep the original PST untouched until the copy passes the verification test. If the copy fails, delete only the copy, reopen Outlook on the original, and retry the backup with Outlook fully closed. For a controlled diagnosis of a persistently locked file,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
