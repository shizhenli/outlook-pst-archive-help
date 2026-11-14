---
title: "PST Export Finishes Without the Expected Folders: A Targeted Fix"
description: "Export completes but folders are missing from the new PST? Follow these checks to diagnose and restore the expected folder tree in classic Outlook."
seo_title: "PST Export Missing Folders? Fix Classic Outlook Archive Export"
seo_description: "Export completes but folders are missing from the new PST? Follow these checks to diagnose and restore the expected folder tree in classic Outlook."
keywords:
  - "outlook pst missing folders"
date: 2026-11-14T19:29:30+08:00
publishDate: 2026-11-14T19:29:30+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You exported a PST archive in classic Outlook, but the new file lacks the folders or subfolders you selected.

## Confirm what was actually exported
Open the new PST in Outlook (File > Open & Export > Open Outlook Data File). Expand every top-level folder. If a parent folder appears but its subfolders do not, the export likely ran in filtered or partial mode. Check the source PST: are the missing folders visible there? If they are, the issue is in the export scope, not corruption.

## Check the export scope and filter
Re-run the export wizard (File > Open & Export > Import/Export). When you reach the folder selection step, verify that each parent and child folder is explicitly checked. A common trap: selecting only a parent does not always include subfolders in classic Outlook. Also inspect the filter option; if a date or category filter was applied, folders with no matching items may be omitted. Choose "Do not import duplicates" only when merging, not for a clean export.

## Verify folder count before and after
Count the folders in the source PST using Folder Properties > Show total number of items, or use the folder list view. Compare with the new PST. If the counts differ, the export did not capture the full tree. This is the exact symptom of **outlook pst missing folders** during archive export.

## Verification test
Create a small test folder in the source PST with one item, export again, and confirm it appears in the new PST. If it does, the original export scope was incomplete. If it does not, stop and seek guided diagnosis before overwriting anything.

## Rollback and recovery
Keep the original PST untouched until verification passes. If the new PST is incomplete, delete it and re-export from the source. Never delete the source archive based on an unverified export. For a controlled diagnosis of your folder tree,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
