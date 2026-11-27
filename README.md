# OctgmFlow

Voice typing for Android, wherever you write.

OctgmFlow adds a floating bubble to your screen. Tap it while you're in WhatsApp or any other app, speak, and your words are inserted directly into the text field. There is no keyboard switching and no copy-pasting.

## Features

- **Floating bubble.** Available over any app, one tap away. Long-press and drag to switch languages or formatting modes.
- **Speech to text.** Speak naturally and get written text back, powered by ElevenLabs and Groq.
- **Direct insertion.** Text is typed into the active input field automatically.
- **Works across apps.** Messaging, notes, code editors, email, browsers, and anywhere else you can type.

## Requirements

- Android device (Android 7.0 or higher)
- Internet connection
- An [ElevenLabs](https://elevenlabs.io) API key (and optionally a [Groq](https://console.groq.com) API key for formatting modes)

## Installation

1. Download the latest APK (`OctgmFlow_v244.apk`) from the [Releases](../../releases) page.
2. Open the file on your device and install it. If prompted, allow installs from unknown sources for your browser or file manager.
3. Launch OctgmFlow.

## Setup

### 1. Grant permissions

OctgmFlow needs the following permissions to work. The app will guide you through each one.

| Permission | Purpose |
| --- | --- |
| Display over other apps | Shows the floating bubble on top of other apps |
| Accessibility service | Inserts transcribed text into the active text field |
| Microphone | Records your voice |

### 2. Add your API keys

1. Sign in to your ElevenLabs account (and Groq console if using formatting modes) and copy your API key.
2. In OctgmFlow, open **Settings**.
3. Paste the key into the **ElevenLabs API key** (and **Groq API key**) field and save.

## Usage

1. Open any app and tap into a text field.
2. Tap the OctgmFlow bubble and start speaking.
3. Tap the confirm button to stop. The transcribed text appears in the field.
4. Long-press the bubble to switch between formatting modes (Clean, Formal, Bullet, Raw) or language flows.

## Privacy

Your API keys are stored locally on your device. Recorded audio and text are sent directly to ElevenLabs and Groq solely to produce and format your transcription, subject to the [ElevenLabs privacy policy](https://elevenlabs.io/privacy) and [Groq privacy policy](https://groq.com/privacy-policy/). OctgmFlow does not run its own servers.

## Troubleshooting

- **The bubble doesn't appear.** Confirm that "Display over other apps" is enabled for OctgmFlow in system settings.
- **Text isn't inserted.** Make sure the accessibility service is turned on and that a text field is focused.
- **Transcription fails.** Check your internet connection and verify that your API key is valid and has available credits.

## Contributing

Bug reports and feature requests are welcome. Please open an [issue](../../issues) with as much detail as you can, including your Android version and device model.

## Author

Developed by **Tu ij bi Al Najah**.
