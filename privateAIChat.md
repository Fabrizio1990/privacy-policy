# Privacy Policy - Private AI Chat

**Last updated:** March 2026

## Overview

Private AI Chat is an Android application that enables private AI-powered conversations. The app prioritizes user privacy by offering on-device AI processing alongside optional cloud-based AI services.

## Data Collection and Processing

### On-Device AI Processing
- AI conversations processed locally using on-device models (MediaPipe/Gemma) **never leave your device**
- No data is sent to external servers when using on-device models
- All conversation history is stored locally on your device using AsyncStorage

### Cloud AI Processing (Optional)
- When using Google Gemini API (cloud provider), your messages are sent to Google's servers for processing
- This is **opt-in only** and requires you to provide your own API key
- Google's privacy policy applies to data processed through their API: https://policies.google.com/privacy

### Audio Recording (Whisper Transcription)
- The app requests microphone access for voice-to-text transcription
- Audio is processed **entirely on-device** using the Whisper model
- Audio recordings are temporary and deleted after transcription
- No audio data is sent to external servers

### Device Information
- The app reads device RAM and storage capacity to determine compatible AI models
- This information is used locally only and is never transmitted

### Network Access
- Internet access is used for:
  - Downloading AI models (one-time, from Hugging Face repositories)
  - Cloud AI API calls (only when cloud provider is configured)
- No analytics, tracking, or telemetry data is collected or transmitted

## Data Storage

- All app data (conversations, settings, model preferences) is stored locally on your device
- Data can be cleared by uninstalling the app or clearing app data in Android settings
- AI model files are stored in the app's private directory

## Cross-App Model Sharing

- If you have multiple apps from the Local AI family installed, they may share downloaded AI model files with each other to avoid redundant downloads
- This sharing happens entirely on-device via Android's ContentProvider mechanism
- No data leaves your device during this process

## Third-Party Services

The app does not integrate any:
- Analytics services
- Advertising networks
- Crash reporting services
- Social media SDKs

## Data Retention

- All data is stored locally and retained until you delete it
- Uninstalling the app removes all associated data

## Children's Privacy

This app is not directed at children under 13. We do not knowingly collect information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

For questions about this privacy policy, please open an issue on the project's GitHub repository.
