---
title: "Fix 'Archive Cannot Be Opened' with ScanPST: A Controlled Diagnosis"
description: "Troubleshoot 'archive cannot be opened' in classic Outlook using ScanPST. Step-by-step checks, exact result interpretation, verification test, and rollback note."
seo_title: "Outlook PST Repair ScanPST Errors: Fix Archive Won't Open"
seo_description: "Troubleshoot 'archive cannot be opened' in classic Outlook using ScanPST. Step-by-step checks, exact result interpretation, verification test, and rollback note."
keywords:
  - "outlook pst repair scanpst errors"
date: 2026-11-15T18:48:51+08:00
publishDate: 2026-11-15T18:48:51+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You try to open your local archive PST in classic Outlook, but it reports the file cannot be opened or is corrupt, leaving you stuck before any controlled diagnosis. Here is a focused way to use the built-in repair tool without guessing.

## Confirm the file and lock state
First, close Outlook completely. Locate the PST (File > Account Settings > Data Files for the path). Right-click the file in File Explorer and check Properties > Details for size and modified date. If Outlook or any sync tool still holds it, you will get a sharing violation. End any lingering outlook.exe process in Task Manager, then retry opening the archive once. If it still fails, proceed to repair.

## Run ScanPST and read the result
Start ScanPST.exe (search for it, or find it under the Office root\OfficeXX folder). Browse to the PST, click Start, and let it finish. If it reports errors and offers repair, run it and note the log path. If it says no errors but Outlook still refuses the file, the problem is likely profile or permissions, not corruption. This is where **outlook pst repair scanpst errors** usually surface as a mismatch between the scan result and Outlook's behavior.

## Verification test
After repair, reopen Outlook and open the archive folder. Confirm you can expand the folder tree and preview one recent message. If it opens, the fix held.

## Rollback and recovery
Before repairing, copy the PST to a backup location. If ScanPST makes things worse, restore that copy and do not run repair again on the same file. For persistent cases,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before further changes.
