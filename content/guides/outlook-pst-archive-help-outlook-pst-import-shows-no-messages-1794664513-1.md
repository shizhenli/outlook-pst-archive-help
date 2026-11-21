---
title: "Outlook PST Import Shows No Messages: A Targeted Fix"
description: "Import wizard finished but your Outlook PST shows no messages? Follow these targeted checks to confirm where the mail went and restore the expected result."
seo_title: "Outlook PST Import Shows No Messages: Fix It Step by Step"
seo_description: "Import wizard finished but your Outlook PST shows no messages? Follow these targeted checks to confirm where the mail went and restore the expected result."
keywords:
  - "outlook pst import shows no messages"
date: 2026-11-21T15:08:05+08:00
publishDate: 2026-11-21T15:08:05+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

**outlook pst import shows no messages**. You ran the import wizard on your classic Outlook PST archive, it completed without an error, but the target mailbox still shows no imported mail.

## Confirm the import target and view
First, check which folder you selected as the destination. In Outlook, right-click the target mailbox, choose Properties, and note the folder path. Then open File > Open & Export > Import/Export and repeat the wizard only to the point where it shows the destination folder; cancel before finishing. If the destination is a subfolder rather than the mailbox root, the messages may be hidden deeper in the tree. Also switch the view to All Mail Items or reset the current view, because a filtered or grouped view can make imported items appear absent.

## Check the PST file itself
Open the source PST directly via File > Open & Export > Open Outlook Data File. If the messages appear there, the import copied them but the target view or folder is wrong. If the PST opens empty, the file may be damaged or the wrong file was selected. Run Scanpst.exe on a copy of the PST and review the log for repaired items.

## Verification test
Create a temporary subfolder under the target mailbox, import a small known PST into it, and confirm the count in Folder Properties. If that works, the original import likely went to a different folder or profile.

## Rollback and recovery
Before retrying, export the current target mailbox to a backup PST. If duplicate or misplaced items appear, delete only the imported folder and restore from that backup.

If the imported pst shows no messages after these checks, stop retrying and capture the wizard destination, folder path, and PST size for diagnosis.

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with those details.
