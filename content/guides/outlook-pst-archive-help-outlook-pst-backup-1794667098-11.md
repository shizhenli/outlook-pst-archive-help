---
title: "PST Backup Conflicts With an Open Outlook: Resolve the Lock Safely"
description: "A backup copy of your PST is locked or inconsistent because Outlook is running. Follow these checks to confirm the conflict, close Outlook safely, and verify a clean backup."
seo_title: "Outlook PST Backup Locked While Outlook Is Open: Fix"
seo_description: "A backup copy of your PST is locked or inconsistent because Outlook is running. Follow these checks to confirm the conflict, close Outlook safely, and verify a clean backup."
keywords:
  - "outlook pst backup"
date: 2026-11-25T10:03:22+08:00
publishDate: 2026-11-25T10:03:22+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive, but the copy is locked or inconsistent because Outlook is still open, and you stopped before completing a controlled diagnosis.

## Confirm the conflict

First, check whether Outlook is actually holding the file. Open Task Manager and look for outlook.exe under Processes. If it is present, the PST is still mounted, and any copy tool will either fail or capture a half-written file. Close Outlook from File > Exit, then confirm outlook.exe disappears from Task Manager. If it remains, end the process and wait ten seconds.

Next, verify the PST path. In Outlook, go to File > Account Settings > Data Files and note the exact location. Compare it with the source path in your backup tool. A mismatch means you may be backing up a stale copy while Outlook writes to another file.

## Run the backup and interpret the result

With Outlook fully closed, run your backup again. A clean result is a copy that completes without a lock warning and whose size matches the source PST within a few kilobytes. If the tool still reports a lock, check for a second process: search for any sync client, antivirus scanner, or search indexer touching the same folder, and pause it temporarily. If the copy completes but the size differs sharply, treat it as inconsistent and do not rely on it.

## Verify the backup

Open the copied PST in Outlook via File > Open & Export > Open Outlook Data File. Expand the folder tree and open two or three recent messages. If they open normally, the copy is usable. For a repeatable **outlook pst backup**, close Outlook before every run rather than backing up a live file.

## Rollback note

If verification fails, delete the bad copy and keep the original PST untouched. Do not overwrite your only archive with an unverified copy. If the original now shows errors, stop and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
