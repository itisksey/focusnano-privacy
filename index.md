---
title: Privacy Policy for FocusNano Widget
---
# Privacy Policy for FocusNano Widget

Effective date: 22.11.2026

Publisher: ksey

This Privacy Policy explains how FocusNano Widget ("FocusNano" or "the app") handles information when you use the app on Windows.

## 1. Overview

FocusNano is a local Pomodoro timer. It works without an internet connection or a user account.

The app does not include advertising, analytics, tracking technologies, or automatic reporting of usage data or crashes to the publisher. It does not send your settings, screen images, or mouse input to the publisher or other external recipients.

## 2. Settings stored on your device

FocusNano saves the following preferences locally:

- Focus and break durations.
- Widget position.
- The "Always on top" preference.
- Progress indicator color.

These settings are used to restore your preferences when you reopen the app. The app does not maintain a history of completed focus sessions.

FocusNano stores your preferences locally on your device in the app's local data folder. These settings are not transmitted to the publisher.

Settings are stored as a local JSON file without additional app-level encryption. Access is governed by Windows file permissions.

## 3. Screen processing for automatic contrast

To keep the transparent widget readable, FocusNano periodically captures the small screen region occupied by the widget and measures the brightness of selected background pixels.

The captured region may include content from other applications visible behind the widget. FocusNano uses it only to measure background brightness and adjust contrast.

This processing takes place entirely in memory on your device. Images are not saved to files or transmitted. The app does not perform text recognition or analyze the meaning of content displayed behind the widget.

Screen sampling stops while the widget is hidden. You can stop all app processing by selecting "Exit" in its menu or tray menu.

## 4. Mouse input and Windows integration

FocusNano uses a system-wide Windows mouse event handler to support hovering, clicking, dragging the transparent widget, and dismissing its menu. This handler receives pointer positions and mouse events, including events outside the widget, to determine whether interaction with the app is required.

During normal use, mouse input is processed locally without maintaining an input history. An optional diagnostic mode can output widget button actions and drag offsets locally.

The app does not record keystrokes or build a history of your activity in other applications.

FocusNano also reads local Windows information, including display layout, theme, window events, and the current user and session identifiers. This information supports positioning, appearance, and ensuring that only one app instance runs within the relevant Windows session. These identifiers are not used for tracking or sent to the publisher.

## 5. Notifications and startup

FocusNano uses Windows notifications to display timer completion messages and related actions. Notification content includes the timer stage, next interval duration, and an identifier used to handle notification actions.

If you enable "Start with Windows," Windows manages that preference. This option is off by default.

Windows and Microsoft Store may independently process information for operating system services, app distribution, updates, and diagnostics under the [Microsoft Privacy Statement](https://www.microsoft.com/en-us/privacy/privacystatement).

## 6. Retention and your controls

Saved preferences remain on your device until changed or deleted. To remove them manually, close FocusNano and delete the settings.json file from the app's local data folder. The app will use default settings the next time it starts.

## 7. Contact

For questions about this Privacy Policy, contact ksey at itisksey@gmail.com.
