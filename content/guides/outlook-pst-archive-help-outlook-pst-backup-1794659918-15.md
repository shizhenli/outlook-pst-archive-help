---
title: "PST Backup Conflicts With an Open Outlook: Resolve the Lock Before Diagnosis"
description: "Fix a locked or inconsistent PST backup that conflicts with an open Outlook session. Step-by-step checks, result interpretation, verification, and rollback guidance."
seo_title: "Outlook PST Backup Locked or Inconsistent While Outlook Runs"
seo_description: "Fix a locked or inconsistent PST backup that conflicts with an open Outlook session. Step-by-step checks, result interpretation, verification, and rollback guidance."
keywords:
  - "outlook pst backup"
date: 2026-11-18T10:12:53+08:00
publishDate: 2026-11-18T10:12:53+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but the copy is locked or inconsistent because Outlook is still running, and you want a clean resolution before any deeper diagnosis.

## Confirm the conflict

First, close Outlook completely. Then open Task Manager and look for any outlook.exe process still listed. If one remains, right-click it and choose End task. Next, check the backup destination: if the .pst copy is present but its timestamp is older than your last Outlook session, the backup captured a stale or partial state. Also confirm the source PST path in Outlook under File > Account Settings > Data Files, so you are backing up the correct archive rather than a secondary file.

## Interpret what you see

If the backup file size is zero or far smaller than the source PST, treat the copy as invalid and delete it. If Windows reports the file is in use, the lock came from the open Outlook session, not from the backup tool. A timestamp that matches the source PST after Outlook is closed indicates a clean copy.

## Run the verification test

With Outlook closed, copy the PST to a test folder, then reopen Outlook and confirm your folders and recent mail appear normally. Open the copied file only through a separate Outlook profile, not your live one, and check that the Inbox and Sent Items counts match. If they do, the backup is usable.

## Roll back safely

If the copied PST fails to open or shows missing items, discard it and keep the original archive untouched. Do not overwrite the source. Re-run the **outlook pst backup** only after Outlook is fully closed, and verify the new copy before relying on it. If the conflict persists,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
