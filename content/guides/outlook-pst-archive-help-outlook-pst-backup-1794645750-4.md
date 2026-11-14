---
title: "PST Backup Conflicts With an Open Outlook: A Controlled Fix"
description: "Resolve a locked or inconsistent PST backup while classic Outlook is running. Step-by-step checks, result interpretation, verification, and rollback guidance."
seo_title: "Outlook PST Backup Conflicts With Open Outlook — Fix Locked or Inconsistent Copies"
seo_description: "Resolve a locked or inconsistent PST backup while classic Outlook is running. Step-by-step checks, result interpretation, verification, and rollback guidance."
keywords:
  - "outlook pst backup"
date: 2026-11-14T19:29:30+08:00
publishDate: 2026-11-14T19:29:30+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but the copy is locked or inconsistent because Outlook is still open, and you want a controlled diagnosis before changing anything.

## Confirm the conflict

First, close Outlook completely. Check Task Manager for any remaining outlook.exe process and end it only if it persists after a normal close. Then inspect the backup destination: if the copied PST is 0 KB, smaller than the source, or cannot be opened, the backup ran while Outlook held the file. Compare the source PST size in File Explorer with the backup size. A matching size and a readable file indicate a clean copy; a mismatch confirms the open-Outlook conflict.

## Separate backup from the live profile

Do not back up the PST in place while Outlook uses it. Close Outlook, wait for the process to exit, then copy the PST to a different drive or folder. If you need Outlook running, use a file-copy tool that supports volume shadow copies, or export to a new PST and back up that export instead. This keeps your **outlook pst backup** from competing with the live profile lock.

## Verification test

Reopen Outlook and confirm your folders and recent mail are present. Then open the backup copy in a separate Outlook profile or with a PST viewer. If the backup opens and shows the same folder tree and item counts, the conflict is resolved. If it still fails, delete the inconsistent copy and repeat the closed-Outlook copy once.

## Rollback and recovery

Keep the original PST untouched until the backup verifies. If the backup is corrupt, discard it rather than overwriting the source. If Outlook reports the profile PST as damaged after the attempt, restore from your last known-good copy before making further changes. For a guided diagnosis,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
