---

<img width="1536" height="1024" alt="ChatGPT Image Mar 7, 2026, 12_17_24 AM" src="https://github.com/user-attachments/assets/291c51fd-4564-4a7e-8cc6-0f7bb7af6c65" />

---

# YouTube Video & Audio Downloader (Google Colab)

A simple Python automation script that allows you to download **YouTube videos in MP4 format** or **extract audio in MP3 format** using **yt-dlp** and **ffmpeg**.

This script is designed to run easily on **Google Colab**, so you don't need to install any software on your computer.

---

## Features

- Download **YouTube videos in the highest available quality (MP4)**
- Extract **audio as MP3 with high bitrate**
- Automatically removes old files to avoid download conflicts
- Simple **1-click format selection**
- Works directly inside **Google Colab**
- Automatically downloads the final file to your computer

---

## Technologies Used

- **Python**
- **yt-dlp** – for downloading video/audio from YouTube
- **ffmpeg** – for audio/video processing and conversion
- **Google Colab** – for running the script in the cloud

---

## How to Use

### Step 1 — Open Google Colab
Go to:

https://colab.research.google.com/

---

### Step 2 — Create a New Notebook
Create a **new notebook** and paste the script into a cell.

---

### Step 3 — Add the YouTube URL
Replace the URL inside the script with the video you want to download.

Example:

```python
url = "PASTE_YOUR_YOUTUBE_VIDEO_URL_HERE"
