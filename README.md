# MULTI-PLATFORM DOWNLOADER

**A simple, fast, and all-in-one video & audio downloader for Windows.**

---

## About The Project

MULTI-PLATFORM DOWNLOADER is a Windows application designed to make downloading videos and extracting audio easier through a simple terminal interface.

It combines video downloading, MP3 extraction, multiple audio downloads, queue management, automatic file organization, and download history in one application.

## Features

- Download single videos.
- Extract audio as MP3.
- Download multiple audio files.
- Manage download queues.
- Automatically organize downloaded files.
- View download history.
- Retry failed downloads.
- Check for yt-dlp updates.
- Simple and easy-to-use terminal interface.
- Opens in a maximized window.

## Supported Platforms

The application is designed to support media links from:

- YouTube
- TikTok
- Instagram
- Facebook
- X (Twitter)

*Platform support depends on yt-dlp compatibility and platform restrictions.*

---

## Download & Installation

Follow these steps to install the application:

**Step 1 — Download**

1. Open the [Latest Releases](https://github.com/yousefgamalhegran/MULTI-PLATFORM-DOWNLOADER/releases) page.
2. Find the latest version.
3. Download the application archive file (`.rar`).

**Step 2 — Extract the Files**

1. Locate the downloaded `.rar` file.
2. Right-click the file.
3. Select **Extract Here** or **Extract to...** using WinRAR or 7-Zip.
4. Wait until extraction is complete.

**Step 3 — Run the Application**

1. Open the extracted application folder.
2. Find `MULTI-PLATFORM DOWNLOADER.exe`.
3. Double-click the EXE file.
4. The application should open in a maximized terminal window.

**Important:**
- Do not move the EXE file separately from the other application files.
- Keep the `_internal` and `ffmpeg` folders together with the EXE.
- Do not delete any required application files.
- A separate Python or FFmpeg installation should not be necessary when using the packaged release.

---

## How To Use

After launching the application, you will see the main menu.

### Main Menu Options

| Number | Function |
|---|---|
| 1 | Download Single Video |
| 2 | Download Queue |
| 3 | Download Audio Only (MP3) |
| 4 | Download Multiple Audio Files (MP3) |
| 5 | Download Manager |
| 6 | Settings |
| 7 | Download History |
| 8 | Retry All Failed Downloads |
| 9 | Clear Download History |
| 10 | Check for Updates (yt-dlp) |
| 0 | Exit |

### 1. Download a Single Video

1. Select option `1`.
2. Paste the video URL.
3. Follow the quality selection prompts.
4. Wait for the download to finish.
5. Find the downloaded video in the Videos folder.

### 2. Download Queue

1. Select option `2`.
2. Add the video links you want to download.
3. Follow the prompts to manage the queue.
4. Start the download process.
5. Wait for the queued downloads to finish.

### 3. Download Audio Only (MP3)

1. Select option `3`.
2. Paste the video URL.
3. The application will process the link as an audio download.
4. Wait until the MP3 file is ready.
5. Find the audio file in the Audio folder.

### 4. Download Multiple Audio Files

1. Select option `4`.
2. Enter the first video URL.
3. Continue entering the other URLs.
4. When you finish, submit an empty line by pressing Enter.
5. The application will process the audio downloads.
6. Find the downloaded MP3 files in the Audio folder.

### 5. Download Manager

Select option `5` to access the download management features available in the application.

### 6. Settings

Select option `6` to access the application settings.

### 7. Download History

Select option `7` to view previous download records.

### 8. Retry Failed Downloads

Select option `8` to retry downloads that previously failed.

### 9. Clear Download History

Select option `9` to clear the saved download history.

### 10. Check for Updates

Select option `10` to check for available yt-dlp updates.

---

## Downloaded Files Location

The application organizes downloaded files into separate folders:

```text
MULTI-PLATFORM DOWNLOADER/
│
├── Audio/
│   └── Downloaded MP3 files
│
├── Videos/
│   └── Downloaded video files
│
├── ffmpeg/
│
├── _internal/
│
└── MULTI-PLATFORM DOWNLOADER.exe
```

*The exact download folder location depends on the application configuration.*

---

## System Requirements

- Windows 10 or Windows 11 (64-bit).
- Internet connection.
- No separate Python installation should be required for the packaged release.
- FFmpeg is included in the distributed application package.

## Project Information

**Version:** v1.0.0

**Status:** Initial Public Testing Release.

This application is currently being tested on different Windows devices. Compatibility and performance are still being evaluated.

## Feedback & Bug Reports

If you encounter a problem:

1. Visit the [Issues](https://github.com/yousefgamalhegran/MULTI-PLATFORM-DOWNLOADER/issues) page.
2. Click **New Issue**.
3. Describe the problem.
4. Include a screenshot of the error if possible.
5. Mention your Windows version.

Your feedback helps improve the application.

## Disclaimer

This application is intended for downloading content that you own or have permission to download. Users are responsible for complying with applicable copyright laws and the terms of service of the platforms they use.

---

## Developer

**Yousef Gamal Hegran**

GitHub: [@yousefgamalhegran](https://github.com/yousefgamalhegran)

---

**Thank you for trying MULTI-PLATFORM DOWNLOADER!** ❤️
