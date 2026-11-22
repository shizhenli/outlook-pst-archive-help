---
title: "PST Export Completes but Folders Are Missing: A Controlled Fix"
description: "Export finishes but selected folders are absent from the new PST? Follow these targeted checks to restore the expected folder tree and verify the result."
seo_title: "Outlook PST Export Stops Halfway: Restore Missing Folders"
seo_description: "Export finishes but selected folders are absent from the new PST? Follow these targeted checks to restore the expected folder tree and verify the result."
keywords:
  - "outlook pst export stops halfway"
date: 2026-11-22T09:03:24+08:00
publishDate: 2026-11-22T09:03:24+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a PST export from classic Outlook, watched it complete, but the new file is missing folders you explicitly selected, and now you need to restore the expected outcome before diagnosing further.

## Confirm what was actually selected

In Outlook, right-click the source PST root, choose Export, and note whether the export wizard shows the full folder tree or only top-level items. If subfolders are collapsed or unchecked, the export will finish without them. Re-run the export and expand every branch before selecting. Result interpretation: if the tree shows all folders checked, the selection is not the cause and you should move to the next check.

## Check for filters and view limits

Open the source PST and switch to a folder that went missing. Confirm the view is not filtered (View > Reset View) and that the folder contains items. An empty or filtered folder can be skipped silently. If items appear after resetting the view, re-export and compare counts.

## Test with a small controlled export

Create a new PST, export only one parent folder with two subfolders, then open the result via File > Open & Export > Open Outlook Data File. Count the subfolders and a sample of messages. If the small export preserves structure, the original failure is likely size or corruption related; if it also drops subfolders, treat the source PST as suspect. This is where an **outlook pst export stops halfway** pattern often becomes visible in logs.

## Recovery note

Keep the original PST untouched and work from a copy. If the controlled test fails, run Scanpst.exe on the copy before retrying, and retain the previous export as a rollback point.

If the folder tree still will not export,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with your Outlook version and the exact folders missing.
