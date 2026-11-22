---
title: "ScanPST Errors When Repairing an Archive PST That Won't Open"
description: "Troubleshoot ScanPST errors when your archive PST won't open in classic Outlook. Follow targeted checks, interpret results, and verify the repair safely."
seo_title: "Fix ScanPST Errors: Archive PST Won't Open in Outlook"
seo_description: "Troubleshoot ScanPST errors when your archive PST won't open in classic Outlook. Follow targeted checks, interpret results, and verify the repair safely."
keywords:
  - "outlook pst repair scanpst errors"
date: 2026-11-22T10:03:30+08:00
publishDate: 2026-11-22T10:03:30+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

Your archive PST won't open in classic Outlook, and you're stuck before a controlled diagnosis is complete.

## Confirm the failure and isolate the file

Close Outlook. Locate the archive PST (File > Account Settings > Data Files, or search for .pst). Copy it to a local folder—never repair the only copy. Right-click the copy, choose Properties, and note the size. If it's 0 KB or the path is on a network drive, move it local first; ScanPST often fails on unstable paths. Then run ScanPST.exe (search for it in the Office folder) and point it at the copy. If it reports "file not found" or access denied, the path or permissions are the issue, not corruption.

## Interpret ScanPST results before repairing

Run the scan without repair first. A clean result means the file is readable—your open error is likely a profile or lock issue, so skip repair. If errors appear, note the count. Choose repair only on the copy. If ScanPST crashes or loops with **outlook pst repair scanpst errors**, stop: repeated repair attempts can further damage the file. Check free disk space (at least twice the PST size) and that Outlook is fully closed in Task Manager.

## Verification test

After repair, open the copy in Outlook via File > Open > Outlook Data File. Confirm the folder tree and a few recent messages appear. If it opens, the original was corrupt; replace it only after backing up the original.

## Rollback and recovery

If the repaired copy still won't open, restore your backup and do not overwrite the original. Keep the failed copy for diagnosis. For a guided review of the scan log,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
