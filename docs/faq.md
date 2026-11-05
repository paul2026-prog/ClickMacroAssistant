# Frequently asked questions

## Which systems are supported?

The current edition is a Windows desktop application. No macOS, Linux, Android, or iOS edition is included.

## Do I need an installer, Python, an account, or an activation code?

No. Extract the purchased ZIP and run `ClickMacroAssistant.exe`. The core clicking, recording, and local macro features work offline. A macro that opens a website still needs internet access.

## Are the main clicker and Automation Studio shortcuts the same?

No. The main window uses **F8** for start/stop and **F9** for emergency stop. Automation Studio uses **F6** to end recording, **F7** to replay, and **F10** to stop. Shortcut conflicts with other running software can prevent registration or use.

## Why might a recorded macro click the wrong item?

Recorded actions depend on the starting desktop and target application. A window may open in a different state; a dynamic menu may appear later or change order; a file name may change; or the computer may respond at a different speed. Restore the original starting state, add waits before sensitive steps, and re-record short sections when necessary. Window-relative positioning helps with some moved windows but cannot guarantee replay across changing layouts.

## Will it work with every application or game?

Compatibility is not guaranteed. Protected or elevated windows may require you to run the app as administrator, and some applications may not accept simulated input. Test each workflow on disposable data before relying on it.

## How do I move a macro to another computer?

Copy the `.mcs` macro file and any BMP images it uses. An image step stores the BMP path, not the image itself, so update the path after moving files. Point lists use `.dat` files.

## Where do I purchase or get download help?

Use the [itch.io product page](https://clickmacroassistant.itch.io/clickmacro-assistant). For product support, email **harsple2026@gmail.com** with the app version, Windows version, and a concise description of what happened. Do not send passwords, payment data, or sensitive recordings.