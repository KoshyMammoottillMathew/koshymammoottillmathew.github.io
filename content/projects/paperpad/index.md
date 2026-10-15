---
title: "PaperPad"
date: 2026-10-15
summary: "Privacy-first digital sticky-note app for iOS, built with SwiftUI and WidgetKit. Notes stay on the user's device with no accounts, analytics, ads, tracking, or external servers."
tags:
  - PaperPad
  - iOS
  - SwiftUI
  - WidgetKit
  - Privacy
  - Open Source
links:
  - type: code
    url: https://github.com/KoshyMammoottillMathew/PaperPad
---

## PaperPad

**PaperPad** is a simple, privacy-first digital sticky-note app for iPhone. It is designed for quick note capture while keeping the user's notes on their device.

### How it works

Users can quickly write and save notes, mark items as completed with a strikethrough, and move through automatically created pages as their notes grow. A WidgetKit extension brings PaperPad notes to the iOS Home Screen and shares the same local App Group storage as the main app.

### Privacy-first architecture

PaperPad is intentionally designed without accounts, analytics, advertising, tracking, telemetry, cloud databases, or external servers. The app does not collect or transmit note contents or personal information. Notes are encoded and stored locally using the shared iOS App Group container so the main app and widget can access the same data.

Home Screen widgets are visible on the device, so users should avoid placing sensitive information in a widget if other people may be able to view their screen.

### Current Features

- Quick note creation and editing
- Persistent local note storage
- Completed-note strikethrough
- Automatic note pages and page history
- Delete with undo support
- iOS Home Screen widget
- Interactive completion controls from the widget
- Shared local App Group storage between app and widget
- No account required
- No analytics, ads, or tracking
- Open-source under the MIT License

### Technology Stack

**Swift · SwiftUI · WidgetKit · App Intents · iOS App Groups**

### Source Code

[View the PaperPad GitHub Repository](https://github.com/KoshyMammoottillMathew/PaperPad)

> **Privacy:** PaperPad's current architecture keeps notes on the user's device and does not include a backend or third-party analytics/tracking SDKs.
