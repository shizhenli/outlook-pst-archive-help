---
title: "Outlook PST Import Shows No Messages: Diagnose Before You Re-Import"
description: "Import wizard finishes but the mailbox stays empty? Follow these checks to confirm where the messages went before you re-import or repair the PST."
seo_title: "Outlook PST Import Shows No Messages: Targeted Diagnosis"
seo_description: "Import wizard finishes but the mailbox stays empty? Follow these checks to confirm where the messages went before you re-import or repair the PST."
keywords:
  - "outlook pst import shows no messages"
date: 2026-11-23T08:03:25+08:00
publishDate: 2026-11-23T08:03:25+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

**outlook pst import shows no messages**. You finished the import wizard and the target mailbox still looks empty, so you are stuck at the point where the imported pst shows no messages and need a controlled check before changing anything.

## Confirm what the wizard actually imported

First, open the import log if Outlook produced one, or re-run the wizard only up to the summary screen and read the folder count and item count it reports. If the count is zero, the wizard read an empty or wrong file; if the count is positive, the items exist and are simply not where you are looking. Do not click Finish twice on the same file.

## Check the target location and view

In classic Outlook, expand the target mailbox or archive and look for a subfolder named after the imported PST, not just the Inbox. Switch the view to All Mail Items or turn off any active filter, then sort by Received date. If messages appear only under a subfolder, the import worked and the issue is placement, not data loss.

## Verify the source PST independently

Close Outlook, locate the original PST, and open it read-only through File > Open & Export > Open Outlook Data File. Count the items in its Inbox. If that file is also empty, the source is the problem and re-importing will repeat the failure.

## Verification test

Send one test message to the target mailbox, confirm it arrives, then import a single small folder from the same PST. If that folder appears, the file is readable and the earlier run targeted the wrong folder or profile.

## Rollback and recovery

Before any retry, copy the current PST and the original archive to a separate drive. If a partial import created duplicates, remove only the imported subfolder, not the whole mailbox. If the source PST fails to open, stop and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running repair tools.
