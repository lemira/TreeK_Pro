# Changelog

## 3.1.0

- Reply to a specific post and edit your own plain-text posts directly in the tree.
- Use **F (Open in forum)** for formatting, links, or attachments.
- The compact form includes a **Subject** field and uses the configured title inheritance and suffix rules.
- The settings window closes after 15 seconds of inactivity by default. Reopen it with **⚙ (Settings)**.
- Supports Kunena 7.0.11, 7.1.0, and 7.1.1.

## 2.0.10

Changes since 2.0.8.

- Added unified support for Kunena 7.0 and 7.1 in one package, with automatic selection of integration files.
- Incorporated Kunena security fixes for permissions, request tokens and escaped template output.
- Added topic and category read-permission checks before TreeK AJAX requests return forum data.
- Added support for Kunena 7.1 notification queues, pending attachments and editor integration.
- Added a system plugin that monitors integration files and reminds administrators to reinstall TreeK after installing or updating Kunena.
- Added an online compatibility catalog on treek.support.
- Clear obsolete reinstall reminders after verified recovery; show update advice when a newer Kunena version is available.
- Preserve versioned backups of original Kunena files across TreeK reinstalls and verify file hashes before restoration.
- Restored optional AJAX diagnostic logging and added troubleshooting guidance to tree refresh error messages.
- Updated installation and compatibility documentation.

## 2.0.8

- Hide TreeK buttons from guests when the TreeK AJAX plugin access level is set to Registered.
- Documented TreeK plugin access level behavior.

## 2.0.7

- Fixed TreeK AJAX URL generation when Joomla is installed in a subdirectory.
- Changed the TreeK installation log to English.
- Added AJAX diagnostics instructions to the installation documentation.

## 2.0.6

- Added compatibility updates for Kunena 7.0.8.
- Clarified that TreeK Pro should be installed again after updating Kunena.

## 2.0

- Added TreeK Pro package build.
- Added forum-view settings.
- Added settings save/restore for Pro.
- Improved reply form behavior with Comfort form header and subject suffixes.
- Added screenshot teaser, flat view, comfort symbols, BBCode/HTML export of tree, topic monitoring, draggable settings, collapsed attachments, and inline action buttons.
- Added package metadata for the TreeK Pro 2.0 release line.
