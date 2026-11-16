---
title: "PST Backup Conflicts With an Open Outlook: Diagnose the Lock Before You Copy"
description: "A practical fix for a PST backup that is locked or inconsistent while classic Outlook is running, with exact checks, a verification test, and a safe rollback step."
seo_title: "Fix PST Backup Locked While Outlook Is Open"
seo_description: "A practical fix for a PST backup that is locked or inconsistent while classic Outlook is running, with exact checks, a verification test, and a safe rollback step."
keywords:
  - "outlook pst backup while outlook open"
date: 2026-11-16T10:03:18+08:00
publishDate: 2026-11-16T10:03:18+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a backup of your local PST archive while classic Outlook was still open, and now the copy is locked or inconsistent.

## Confirm the lock source

Close Outlook completely, then open Task Manager and check for any remaining outlook.exe process. If one is still listed, the PST is still held open and any copy you make may be incomplete. End the process only after Outlook has closed normally. Then try copying the PST again; if the copy succeeds now, the conflict was the open Outlook session, not file damage.

## Check the file and the copy

Right-click the PST, choose Properties, and note its size and modified time. Copy it to a different drive, not the same folder. Compare the copied file size with the original. A smaller copy or a copy that refuses to complete means the file was still in use. Do not overwrite your only good PST with a partial copy; keep the original untouched until the copy matches in size.

## Verification test

Open the copied PST in Outlook using File, Open & Export, Open Outlook Data File. Expand the folder tree and open several recent messages. If folders and mail appear normally, the copy is usable. If Outlook reports the file is in use or cannot open it, delete that copy and repeat after a full Outlook shutdown.

## Rollback note

If a backup attempt left a suspect copy, keep the original PST and remove only the bad copy. Do not run repair tools on the original until you have a verified second copy. For a controlled diagnosis of your specific archive,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).

For a reliable **outlook pst backup while outlook open**, close Outlook first, confirm no outlook.exe remains, then copy and verify the file size before trusting the backup.
