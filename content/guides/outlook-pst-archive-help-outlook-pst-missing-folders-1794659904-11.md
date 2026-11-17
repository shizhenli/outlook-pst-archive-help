---
title: "PST Export Omits Folders: Diagnose the Export Scope Before Re-Exporting"
description: "Export finishes but selected folders are absent? Learn how to check export scope, interpret results, and verify the new PST without losing data."
seo_title: "Outlook PST Missing Folders: Fix Export Scope and Restore the Folder Tree"
seo_description: "Export finishes but selected folders are absent? Learn how to check export scope, interpret results, and verify the new PST without losing data."
keywords:
  - "outlook pst missing folders"
date: 2026-11-17T11:03:20+08:00
publishDate: 2026-11-17T11:03:20+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished an export to a new PST, but the folders you selected are not in the file. The export completed without errors, yet the folder tree is incomplete. Before re-exporting, diagnose the export scope so you do not repeat the same result.

## Check the Export Scope First

In classic Outlook, open File > Open & Export > Import/Export > Export to a file. Choose the same source and click Next until you reach the folder list. Expand every branch. A checked parent does not always include subfolders if a child was unchecked earlier. Confirm that each target folder and its subfolders carry a check mark. If a subfolder is unchecked, the export will finish but omit it. This is the most common cause of **outlook pst missing folders** after a completed export.

## Interpret the Result

If the folder list shows unchecked children, the export scope is the cause. If all boxes are checked and folders are still absent, check the new PST: open it with File > Open & Export > Open Outlook Data File. Expand the top-level folders. Missing subfolders under a present parent point to a scope issue; a completely absent top-level folder points to a wrong source selection.

## Verification Test

Create a small test folder with one message inside the source PST. Export only that folder to a new test PST. Open the test PST and confirm the folder and message appear. If they do, repeat the full export with every subfolder checked. If they do not, stop and seek a controlled diagnosis.

## Rollback Note

Do not delete the original PST or overwrite the incomplete export. Keep both files until the verification test passes. If the re-export still omits folders, preserve the incomplete PST as evidence and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
