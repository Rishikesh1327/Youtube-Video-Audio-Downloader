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

---

### Step 4 — Run the Script

Run the notebook cell.

You will see the following option:

1 = Video (MP4 Highest Quality)  
2 = Audio (MP3 High Bitrate)

Enter:

- **1** → Download video  
- **2** → Download audio  

---

### Step 5 — Download the File

Once the process finishes, the script will automatically **download the generated file to your computer**.

---

## Example Use Cases

This script can be useful for:

- Downloading videos for **offline viewing**
- Extracting audio from **lectures**
- Saving **podcasts**
- Creating **MP3 files from videos**
- Learning **Python automation**

---

## How the Script Works

The script performs the following steps:

1. Installs required tools (`yt-dlp` and `ffmpeg`)
2. Removes old files to prevent download conflicts
3. Accepts user input for download format
4. Downloads the highest quality video or audio
5. Converts audio into MP3 format
6. Detects the newest file created
7. Automatically downloads the file to the user’s computer

---

## Important Note

YouTube typically stores audio using **Opus format (~160 kbps)**.

When converting to **MP3**, the script encodes the audio at **320 kbps**, but the final quality depends on the original source audio available on YouTube.

---

## Disclaimer

This project is intended **for educational purposes only**.

Please respect **YouTube's terms of service** and only download content you have permission to use.

---

## Author

**Rishikesh Dighe**

Data Analyst | Tech Enthusiast | Automation Learner

LinkedIn  
https://www.linkedin.com/in/rishikesh-dighe/

GitHub  
https://github.com/Rishikesh1327

---

## If you found this useful

⭐ Consider **starring this repository** to support the project.
