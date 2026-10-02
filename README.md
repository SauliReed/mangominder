# MangoMinder

MangoMinder is a Chrome extension that helps users track their task workflow on supported Multimango and Parimango pages.

This repository contains the public MangoMinder website and privacy policy. It does not contain confidential platform content or account credentials.

## Features

- Automatic elapsed-time tracking using supported task-acquisition and heartbeat responses.
- Timing that works when no task time limit is supplied.
- A separate time-limit display when one is available.
- A toolbar badge showing elapsed whole minutes.
- An optional draggable page timer.
- Submit-click counting with configurable button labels.
- Optional chime reminders.
- A dark-mode preference saved for each supported site.

An existing account with the supported platform is required to use its task workflow. MangoMinder does not provide platform access. The submit counter records matching button clicks rather than server-confirmed task completion.

## Public website

The planned website consists of:

- `index.html` — project overview and support contact.
- `privacy.html` — the extension's privacy policy.

These website files will be added separately. The Chrome Web Store listing link will be added once the extension is published.

## Publish with GitHub Pages

After adding the website files to the repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the **main** branch and **/(root)** folder, then save.
4. Use the published URL shown in GitHub Pages settings.
5. Confirm that the homepage and `privacy.html` open without signing in.

Only upload files intended for public access. Do not include task captures, platform payloads, credentials, or private information.

## Privacy

Task-clock state, submit counts, and appearance preferences are stored in browser extension storage. Notification settings and tracked button labels use Chrome sync storage and may sync through the user's Google account when Chrome sync is enabled.

MangoMinder includes no analytics or developer-operated task-data collection endpoint. The full privacy policy will be available on the public website.

## Support

Email: [contact.mangominder@gmail.com](mailto:contact.mangominder@gmail.com)

Publisher: **Foo**

MangoMinder is an independent companion extension and is not an official Multimango or Parimango product.
