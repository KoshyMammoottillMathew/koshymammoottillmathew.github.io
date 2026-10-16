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

### Get PaperPad

PaperPad is currently available as an **open-source iOS project**. You can view the source code, download it, and build the app yourself using Xcode on a Mac.

[**View on GitHub →**](https://github.com/KoshyMammoottillMathew/PaperPad)

[**Download Source Code (.zip) →**](https://github.com/KoshyMammoottillMathew/PaperPad/archive/refs/heads/main.zip)

**App Store — Coming Later**

> PaperPad is not currently distributed through the App Store. The source code is available now for developers who want to build and run the app themselves.

### Build with Xcode

To build PaperPad from source:

1. Download the source code above, or clone the GitHub repository.
2. Open the PaperPad Xcode project on a Mac using Xcode.
3. Select the **PaperPad** app target and open **Signing & Capabilities**.
4. Choose your own Apple **Personal Team** for code signing.
5. Do the same for the **PaperPadWidgetExtension** target.
6. Because App Group identifiers must belong to your own developer account, create your own App Group and replace `group.com.koshymammoottillmathew.PaperPad` in both the PaperPad app and widget targets with your App Group identifier.
7. If Xcode reports that the existing bundle identifiers are unavailable, replace the PaperPad app and widget bundle identifiers with unique identifiers associated with your Apple account.
8. Connect your iPhone to the Mac, select it as the run destination, and press **Run** in Xcode.
9. If prompted on the iPhone, trust the developer certificate under **Settings → General → VPN & Device Management**.
10. After PaperPad opens, add the **PaperPad Notes** widget from the iOS Home Screen widget gallery if you want to use the widget.

A free Apple account can be used for personal development and device testing through Xcode. App Store/TestFlight distribution requires Apple Developer Program membership.

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

PaperPad is open source under the MIT License. The complete project is available on GitHub for inspection, learning, modification, and personal builds.

[**View the PaperPad GitHub Repository →**](https://github.com/KoshyMammoottillMathew/PaperPad)

> **Privacy:** PaperPad's current architecture keeps notes on the user's device and does not include a backend or third-party analytics/tracking SDKs.
