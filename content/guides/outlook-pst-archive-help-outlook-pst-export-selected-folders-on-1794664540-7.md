---
title: "PST Export Finishes Without the Expected Folders: Fixing a Selection That Didn't Stick"
description: "PST export completes but selected folders or subfolders are missing from the new file? Check selection scope, subfolder inclusion, and filters before re-exporting."
seo_title: "Outlook PST Export Selected Folders Only: Missing Folders Fix"
seo_description: "PST export completes but selected folders or subfolders are missing from the new file? Check selection scope, subfolder inclusion, and filters before re-exporting."
keywords:
  - "outlook pst export selected folders only"
date: 2026-11-21T15:11:10+08:00
publishDate: 2026-11-21T15:11:10+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You ran a pst export of chosen folders, but the new file opened without them, and you want the expected folders back before doing anything else.

## Confirm What Was Actually Selected

In Outlook, right-click the archive root and choose New Folder or use File > Open & Export > Import/Export. When the export wizard reaches the folder list, expand every parent node manually. A folder that looks selected at the top level may have its subfolders unchecked. Select the parent, then click the child checkboxes one by one. If a child stays greyed out, the parent is only partially selected, which is a common reason a pst export finishes without the expected folders.

## Check the Filter and Date Range

In the export wizard, open Filter and confirm no date range or category restriction is active. A filter applied to one folder can silently drop messages and make the folder appear empty in the new PST. Clear the filter, then re-run the export to a fresh filename.

## Verify the Result

Open the new PST with File > Open & Export > Open Outlook Data File. Expand the tree and count the folders against your original selection list. If the folder count matches but messages are absent, the filter was the cause. If folders are still missing, the selection did not persist.

## Rollback Note

Keep the original archive untouched until verification passes. If the new PST is wrong, delete only the newly created file, not the source, and repeat the export with a clean selection.

For a controlled diagnosis of your folder tree,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).

When you need **outlook pst export selected folders only**, verify each child checkbox and clear filters before exporting again.
