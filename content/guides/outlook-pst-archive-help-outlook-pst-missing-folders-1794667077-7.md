---
title: "Why Your PST Export Skips Folders (and How to Recover Them)"
description: "PST export finishes but expected folders are absent? Diagnose the export scope, folder selection, and profile issues, then verify and recover safely."
seo_title: "Outlook PST Missing Folders After Export: Targeted Fix"
seo_description: "PST export finishes but expected folders are absent? Diagnose the export scope, folder selection, and profile issues, then verify and recover safely."
keywords:
  - "outlook pst missing folders"
date: 2026-11-24T11:03:32+08:00
publishDate: 2026-11-24T11:03:32+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You ran a PST export from classic Outlook with a local archive, and the progress bar completed, but the new file is missing folders you explicitly selected.

## Confirm what the export actually included

Open the new PST in Outlook via File > Open & Export > Open Outlook Data File. Expand every root node. If the folder tree stops at the root, the export likely used a filter that excluded subfolders. Check the export dialog's folder selection: selecting a parent folder does not always include its children when a filter is active. Re-run the export with the filter cleared and each target folder checked individually.

## Check the source archive state

In the original PST, right-click the archive root and choose Properties to confirm the file path and size. Then run Scanpst.exe against that source file. A clean scan result means the folder structure is intact and the fault lies in export settings. If Scanpst reports errors and repairs them, re-export afterward and compare folder counts.

## Verify the result

Count the top-level folders in the source and the new PST. They should match for the selected scope. Open one known subfolder and confirm at least one message exists. If counts differ, the export scope was wrong, not the data.

## Recovery note

Do not delete the original archive until verification passes. If the new PST is incomplete, discard it and re-export from the untouched source. Keep a copy of the source PST before any repair attempt.

If the folder tree still will not transfer, this points to a profile-level fault rather than a settings error. For a guided diagnosis of **outlook pst missing folders**,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
