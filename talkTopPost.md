# Privacy Policy — Talk to Post

**Last updated:** March 2026

## Overview

Talk to Post is an Android application that helps users transform personal notes and journal entries into social media posts using artificial intelligence. The app prioritizes user privacy by offering on-device AI processing alongside optional cloud-based AI services.

## Data Collection and Processing

### Data Stored Locally

All user-generated content is stored **exclusively on your device** using local storage (AsyncStorage). This includes:

- Journal entries and notes
- Generated social media posts
- App settings and preferences
- Downloaded AI models

**We do not collect, transmit, or store any of this data on external servers.**

### On-Device AI Processing

- AI text generation is processed locally using on-device models (llama.cpp/Qwen) and **never leaves your device**
- No data is sent to external servers when using on-device models

### Cloud AI Processing (Optional)

- When using Google Gemini API (cloud provider), your text input is sent to Google's servers for processing
- This is **opt-in only** and requires you to provide your own API key
- Your API key is stored securely on your device using encrypted storage
- Google's privacy policy applies to data processed through their API: https://policies.google.com/privacy

**You can avoid any cloud data transmission by using only on-device AI models.**

### Audio Recording (Whisper Transcription)

- The app requests microphone access for voice-to-text transcription
- Audio is processed **entirely on-device** using the Whisper model
- Audio recordings are temporary and deleted after transcription
- No audio data is sent to external servers

### Images and Documents

- When attaching images or documents (PDF, TXT, CSV), files are processed locally on your device
- If using Google Gemini API, image/document content may be sent to Google for processing
- No files are uploaded to our servers

### Device Information

- The app reads device RAM and storage capacity to determine compatible AI models
- This information is used locally only and is never transmitted

### Network Access

- Internet access is used for:
  - Downloading AI models (one-time, from GitHub repositories)
  - Fetching the model catalog (periodically, from GitHub)
  - Cloud AI API calls (only when cloud provider is configured)
- No analytics, tracking, or telemetry data is collected or transmitted

## Data We Do NOT Collect

- Personal information (name, email, phone number)
- Location data
- Device identifiers or advertising IDs
- Usage analytics or telemetry
- Crash reports
- Browsing history
- Contact lists

## Data Storage

- All app data (journals, posts, settings) is stored locally on your device
- Data can be cleared by uninstalling the app or clearing app data in Android settings
- AI model files are stored in the app's private directory

## Cross-App Model Sharing

- If you have multiple apps from the Local AI family installed, they may share downloaded AI model files with each other to avoid redundant downloads
- This sharing happens entirely on-device via Android's ContentProvider mechanism
- Only AI model files are shared, never user data or content
- No data leaves your device during this process

## Third-Party Services

The app does not integrate any:
- Analytics services
- Advertising networks
- Crash reporting services
- Social media SDKs

The only optional third-party service is **Google Gemini API**, activated only if you explicitly configure it with your own API key.

## Data Retention

- All data is stored locally and retained until you delete it
- You can delete individual journals, notes, or posts within the app
- Uninstalling the app removes all associated data

## Children's Privacy

This app is not directed at children under 13. We do not knowingly collect information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

For questions about this privacy policy, please open an issue on the project's GitHub repository.
