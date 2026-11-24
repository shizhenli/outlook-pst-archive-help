---
title: "PST Export Skips Selected Folders: Diagnose the Missing Folder Tree"
description: "When a PST export finishes without the expected folders, use this targeted diagnosis to confirm selection scope, subfolder inclusion, and profile behavior before rebuilding the export."
seo_title: "Outlook PST Export Selected Folders Only: Fix Missing Folders After Export"
seo_description: "When a PST export finishes without the expected folders, use this targeted diagnosis to confirm selection scope, subfolder inclusion, and profile behavior before rebuilding the export."
keywords:
  - "outlook pst export selected folders only"
date: 2026-11-24T09:03:27+08:00
publishDate: 2026-11-24T09:03:27+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You ran a PST export with only certain folders selected, but the new file finished without them.

## Confirm what the export actually included

Open the new PST in Outlook and expand every top-level node. If the folders are absent rather than empty, the export scope was narrower than intended. Check the source PST: right-click the parent folder, choose Properties, and note the folder count. Then compare it with the new PST. A lower count means subfolders were excluded at selection time, not lost afterward.

## Check the selection method

In the Export wizard, the include-subfolders option applies to the folder you highlight, not to every checked item. If you selected a parent but left subfolders unchecked, only the parent's direct items export. Re-run the export and explicitly tick each required subfolder, or tick the parent and enable subfolders. This is the most common cause of an **outlook pst export selected folders only** result that looks complete but is incomplete.

## Rule out profile and add-in interference

Start Outlook with the /safe switch, then repeat a small test export of one parent with subfolders enabled. If the test PST now contains the tree, a third-party add-in was altering the export dialog. Disable add-ins one at a time to identify it. If the test still fails, create a new Outlook profile, attach the source PST, and export from there.

## Verification test

Export a single known folder with two subfolders. Open the result and confirm all three nodes appear with matching item counts. Only then repeat the full export.

## Rollback note

Keep the original PST untouched and work from a copy until verification passes. If a re-export overwrites a good file, restore the previous PST from your backup before retrying. For a guided review,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
