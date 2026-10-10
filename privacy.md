---
layout: default
title: Privacy Policy — JLR Unraid Integration
permalink: /privacy/
---

# Privacy Policy

**Effective date: October 10, 2026**

JLR Unraid Integration is a private, noncommercial application that connects the owner's Google Drive account to a self-hosted home server. It is operated for the owner's own personal file transfers, file organization, and media-library management.

## Information accessed

After the owner grants permission through Google's OAuth consent process, the integration may access Google Drive files and folders within the scope of the authorized permissions. The requested permission may allow broad access to Drive content; configuring the automation to operate within designated folders does not technically narrow Google's OAuth permission.

The integration may read file names, folder structures, file contents, and relevant file metadata to identify uploads and transfer them to the owner's server. Depending on the owner's configured workflows, it may create folders, upload files, reorganize or archive processed files, and delete items when explicitly configured to do so.

## How information is used and shared

Drive information is used only to perform the owner's configured file-transfer, organization, and personal media-library workflows. This integration is not offered to other users. The operator does not sell Google user data, use it for advertising, or intentionally disclose it to unrelated third parties. Google processes authorization and Drive API requests under its own terms and privacy policy.

## Storage, security, and retention

Transferred files and operational logs remain under the owner's control on the private home server, subject to the owner's retention and backup settings. OAuth credentials and refresh tokens are stored locally in the owner's rclone configuration and are not published to this website or its public repository.

The owner can delete locally stored files and logs, remove the connection from the server, or revoke the integration's Google access through [Google Account third-party connections](https://myaccount.google.com/connections).

## Changes

The policy may be updated if the integration's capabilities or data handling change. The current policy will be published at this address.

## Contact

Questions about this personal integration can be directed to the operator using the [public project repository](https://github.com/jlr2000/jlr-unraid-oauth).
