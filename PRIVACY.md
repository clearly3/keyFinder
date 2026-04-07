# Privacy Policy - KeyFinder Chrome Extension

**Last Updated:** April 7, 2026

## Overview

KeyFinder is a browser extension that scans web pages for leaked API keys, tokens, and secrets. This privacy policy explains how the extension handles data.

## Data Collection

KeyFinder does **not** collect, transmit, or share any personal data or browsing data with external servers. The extension operates entirely on your local device.

## What Data is Stored Locally

The extension stores the following data locally on your device using Chrome's built-in storage API (`chrome.storage.local`):

- **Search keywords**: User-configured keywords used to identify potential secrets on web pages.
- **Scan findings**: When a potential secret is detected, the extension stores the pattern name, severity level, matched value, page URL, and domain where it was found.

This data never leaves your device.

## How Data is Processed

- All page scanning happens locally within your browser.
- The extension reads page content (scripts, meta tags, form fields, HTML comments, browser storage, and network responses) to match against known secret patterns.
- No page content, scan results, or browsing activity is sent to any external server, API, or third party.

## Data Sharing

KeyFinder does **not** share any data with third parties. Specifically:

- No data is sold to third parties.
- No data is used for advertising or marketing purposes.
- No data is transferred to third parties for reasons unrelated to the extension's core functionality.
- No analytics, telemetry, or tracking is implemented.

## Data Retention

All stored data remains on your local device until you choose to delete it. You can clear all findings at any time using the "Clear All" button in the findings dashboard. Uninstalling the extension removes all stored data.

## Permissions

- **activeTab**: Used to access the current page's content for scanning when the extension is active.
- **storage**: Used to save your keyword preferences and scan findings locally.
- **Host permissions**: The extension runs on all URLs because leaked secrets can appear on any website. No data from these pages is transmitted externally.

## Third-Party Services

KeyFinder does not integrate with, connect to, or send data to any third-party services.

## Changes to This Policy

Any changes to this privacy policy will be reflected in the extension's GitHub repository and the "Last Updated" date above.

## Contact

If you have questions about this privacy policy, contact the developer:

- GitHub: [github.com/momenbasel](https://github.com/momenbasel)
- X: [@momenbassel](https://x.com/momenbassel)
- LinkedIn: [linkedin.com/in/momenbasel](https://www.linkedin.com/in/momenbasel/)
