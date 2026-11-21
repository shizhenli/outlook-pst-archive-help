---
title: "Outlook PST Import Shows No Emails: Diagnose the Empty Target"
description: "Import wizard finished but no mail appears? Check the import target, filter, and view settings to fix outlook pst import no emails."
seo_title: "Outlook PST Import No Emails: Fix Empty Import"
seo_description: "Import wizard finished but no mail appears? Check the import target, filter, and view settings to fix outlook pst import no emails."
keywords:
  - "outlook pst import no emails"
date: 2026-11-21T15:14:26+08:00
publishDate: 2026-11-21T15:14:26+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished the import wizard, but the mailbox shows nothing, and you are stuck at the imported pst shows no messages step.

## Confirm Where the Import Landed

Open the target mailbox, then check the folder list. The wizard may have imported into a subfolder rather than the Inbox. Expand every folder under the mailbox root and look for a new folder named after the PST or "Imported". If you find it, the import worked; the mail is simply in a different folder.

Next, confirm the import option you chose. In the Import and Export Wizard, selecting "Import items into the same folder in" places mail under the current mailbox, while "Import from another program or file" may create a duplicate folder tree. Re-run the wizard only after confirming the destination.

## Check Filters and Views

With the target folder selected, open the View tab and click Reset View. Then check Filter Email or View Settings > Filter; an active filter can hide every imported message. Also clear the search box. If the folder shows a count but no rows, the view is the problem, not the import.

## Verification Test

Create a test folder in the target mailbox, import a small PST containing one known message into that folder, and open it. If the message appears, the original import targeted the wrong folder or was filtered. If it does not, the PST may be corrupt or password-protected.

## Rollback and Recovery

Before retrying, export the current mailbox to a backup PST so you can restore its state. Keep the original PST unchanged. If the test import fails, run Scanpst.exe on a copy of the PST, then repeat the test. For persistent cases where **outlook pst import no emails** despite these checks,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
