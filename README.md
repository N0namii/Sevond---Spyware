# Sevond---Spyware
This script performs screen recording, webcam recording, audio recording, keylogging, captures DNS activity, combines video and audio, and then sends all collected data to a specified email.

## Features

- **Screen Recording**: Captures video from the screen.
- **Webcam Recording**: Captures video from a connected webcam.
- **Audio Recording**: Records sound from the microphone.
- **Keylogger**: Logs all key presses for a specified duration.
- **DNS Activity Capture**: Extracts DNS query data, including domains and IP addresses.
- **Audio-Video Combination**: Combines recorded video and audio into a single file.
- **Email Sending**: Sends all collected files to a specified email address.

## Supported Platforms

- Windows
- macOS
- Linux

## Installation

1. Install the necessary dependencies:

   ```bash
   pip install opencv-python pywin32 pyaudio moviepy pynput requests
   ```

2. Configure the `config` dictionary with your data (e.g., email address and password for sending).

## How to Use

1. Clone or download the repository to your computer.
2. Run the script using Python:

   ```bash
   python sevond.py
   ```

   The script will run indefinitely, periodically performing screen capture, audio recording, webcam video recording, keylogging, and DNS activity logging.

3. After completing all operations, the collected data will be sent to the specified email address.

## Important Notes

- This script is intended for educational purposes only.
- Using this script to record data from other people's devices without permission is illegal and unethical.
- Please ensure that you have permission to use this script in any environment.

## Disclaimer

The author is not responsible for any consequences that may arise from using this script. The script is provided "as is," and its use is at your own risk.

---

