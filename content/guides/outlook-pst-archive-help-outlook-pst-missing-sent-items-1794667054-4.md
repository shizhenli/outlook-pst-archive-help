---
title: "Outlook PST Missing Sent Items: Why Your Export Skips the Sent Folder"
description: "Export finishes but Sent Items is missing from the new PST? Check folder scope, default folder mapping, and view filters before re-exporting. Includes a verification test and rollback note."
seo_title: "Outlook PST Missing Sent Items After Export: Targeted Fix"
seo_description: "Export finishes but Sent Items is missing from the new PST? Check folder scope, default folder mapping, and view filters before re-exporting. Includes a verification test and rollback note."
keywords:
  - "outlook pst missing sent items"
date: 2026-11-24T08:03:27+08:00
publishDate: 2026-11-24T08:03:27+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You exported your classic Outlook mailbox to a new PST, but the finished file has no Sent Items folder, and you need the export to finish with the expected folders intact.

## Confirm the export scope included Sent Items

Open the export wizard again and stop at the folder selection list. Expand the mailbox root and verify Sent Items has a check mark, not a filled square. A filled square means only some subfolders are selected; expand Sent Items and tick every child folder. If Sent Items is greyed out, the profile is using a different delivery store than the one you are exporting.

## Check the default Sent Items mapping

In Outlook, open File, then Account Settings, then Data Files. Confirm the archive or mailbox marked as default contains the Sent Items you expect. Messages sent from another account land in that account's Sent Items, so exporting a secondary store can produce a PST with no Sent folder. Note which store is default before you re-export.

## Rule out a view filter hiding the folder

Open the new PST in Outlook, right-click the root, and choose Properties. Under the Home Page or folder view settings, clear any filter and set the view to Messages. A filtered view can make an imported folder look absent. If the folder appears now, the export was fine and only the view was hiding it.

## Verification test

Send one test message, wait for it to appear in Sent Items, then export only that folder to a scratch PST. Open the scratch file and confirm the test message is present. If it is, repeat the full export with the corrected scope. This isolates whether the problem is selection or store mapping, and explains an **outlook pst missing sent items** result without guesswork.

## Rollback and recovery

Keep the original PST untouched and work on a copy. If the re-export still omits Sent Items, do not delete the source; rename the new PST and retry from the copy. For a guided diagnosis,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
