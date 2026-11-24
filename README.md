🎵 Nashi Music (Mobile)
Nashi Music (Mobile) is a lightweight, local-first music player for Android. Built with Python and Kivy, it is designed for users who want a fast, beautiful, and distraction-free interface without ads, subscriptions, or telemetry.

This is the mobile/Android counterpart to the Nashi Music Desktop app.

Note: This project is currently in Alpha. Features are implemented, but bugs may exist. Please report any issues you find!

✨ Key Features
100% Local & Private: Your music stays on your device. No accounts, no cloud syncing, no tracking, and no ads.

Wide Format Support: Play .mp3, .wav, .ogg, .m4a, and .flac files.

Library Management: Automatically scans your device for music, reads embedded metadata (ID3 tags), and organizes tracks.

Customization: Toggle between Dark and AMOLED themes, choose custom accent colors, and manage playlists.

Advanced Playback: Features include a sleep timer, playback statistics, shuffle, repeat modes, and a seamless mini-player.

Lightweight: Built with Kivy for smooth performance on both low-end and high-end Android devices.

🛠️ Tech Stack & Architecture
Language: Python 3

Framework: Kivy (UI) & KivyMD/Buildozer

Audio/Metadata: Mutagen, SoundLoader

Local Storage: JSON-based atomic file writing for data persistence.

🚀 How to Build from Source
If you want to compile the app yourself, you will need a Linux environment (or WSL on Windows) with Python and Buildozer installed.

Clone the repository:

bash
git clone https://github.com/GinRex12/Nashi-Music-Mobile.git
cd Nashi-Music-Mobile
Install Buildozer and dependencies:

bash
pip install buildozer cython
sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo6 cmake libffi-dev libssl-dev
Build the Android APK:

bash
buildozer -v android debug
📄 License & Usage
Copyright (c) 2026 GinRex12. All rights reserved.

This project is Source-Available. You are permitted to view, copy, and modify the code for personal or internal use only.

You may NOT:

Publish, redistribute, or share the software publicly (e.g., on the Google Play Store, alternative app stores, or code-sharing platforms).

Sell or use the software in commercial products or services.

Please see the LICENSE file for full terms. If you wish to contribute to the project, Pull Requests are welcome.

👨‍💻 Developed By
Nashi Studio

Feel free to open an Issue if you find a bug or have a feature request!

