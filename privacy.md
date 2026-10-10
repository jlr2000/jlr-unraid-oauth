---
layout: default
title: Privacy Policy — JLR Unraid Integration
permalink: /privacy/
---

# Privacy Policy

**Effective October 10, 2026**

JLR Unraid Integration is a personal, noncommercial integration used by the owner of a private Unraid home server to access their own Google Drive account through rclone and Google's OAuth authorization.

## Information accessed

With the account owner's authorization, the integration can access Google Drive files and folders according to the permissions displayed by Google during OAuth consent. The rclone connection may request broad Drive permissions. Limiting actual processing to designated upload folders is an operational practice, not an OAuth restriction.

The workflows process file names and contents required to retrieve uploads, pass torrent submissions to a torrent client, deliver ebooks to a personal library, and potentially archive successfully processed submissions.

## Use and disclosure

Drive data is processed to carry out the owner's requested transfers and home-server automations. The operator does not sell Google user data, use it to serve advertising, or intentionally disclose it to unrelated third parties. Google handles OAuth authorization and Drive API requests under its own policies.

## Storage, protection and retention

Files transferred to the owner's Unraid server and any locally produced processing logs remain under that owner's control. OAuth credentials and refresh tokens are stored on the private server in rclone's configuration and are not stored in this public GitHub repository. Local processing and retention rules are configured by the owner.

The owner can delete imported files or logs, remove the rclone connection, and revoke Google authorization at [Google Account third-party connections](https://myaccount.google.com/connections).

## Changes

The policy may be revised if the integration's functions or data handling change. Updates will be published at this URL.

## Contact

For inquiries, use the [public GitHub repository](https://github.com/jlr2000/jlr-unraid-oauth) to contact the operator.
