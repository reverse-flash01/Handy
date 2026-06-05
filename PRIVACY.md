# Handy Privacy Policy

Last updated: June 2026

## Overview

Handy is an offline speech-to-text application. All processing occurs entirely
on your device. No data of any kind is transmitted to external servers.

## Microphone and Audio

Handy records audio from your microphone only while you are actively holding the
configured keyboard shortcut or using push-to-talk mode. Audio capture stops
immediately when you release the shortcut.

All voice activity detection (using Silero VAD) and speech transcription (using
Whisper or Parakeet models) run locally on your device using locally stored model
files. **No audio is ever sent to any server, cloud service, or third party.**

## Transcription Data

Transcription output is stored locally in your application data directory and is
never transmitted outside your device. You can clear your transcript history at
any time from within the application.

## Application Settings

Your settings and preferences are stored locally on your device and are not
synced to any external service.

## System Permissions

Handy requests the following system permissions:

- **Microphone** — required to capture audio for transcription
- **Accessibility** (macOS/Linux) — required to paste transcribed text into other
  applications via the keyboard shortcut
- **Autostart** (optional) — only if you enable "Launch at login" in settings

No permission data is shared with third parties.

## Third-Party Services

Handy does not integrate with any third-party analytics, advertising, crash
reporting, or tracking services.

Model files are downloaded from `blob.handy.computer` on first use. No
personally identifiable information is sent as part of these downloads.

## Updates

Handy checks for updates by querying the GitHub Releases API
(`github.com/cjpais/Handy/releases`). No user data is included in this request
beyond standard HTTP headers supplied by your operating system.

## Open Source

Handy is fully open source under the MIT license. You can inspect all data
handling in the source code at [github.com/cjpais/Handy](https://github.com/cjpais/Handy).

## Contact

For questions or concerns about this privacy policy, contact:
[contact@handy.computer](mailto:contact@handy.computer)
