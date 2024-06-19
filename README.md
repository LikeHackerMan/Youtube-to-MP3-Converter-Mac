# Youtube-to-MP3-Converter-Mac

This is a Youtube to MP3 converter for Mac, works for Youtube and Youtube Music

# Installation


This Youtube to MP3 converter will require FFMPEG which you can use home brew to install with the code below, I will recommend to use python 3.10.6 which you can install [here](https://www.python.org/downloads/release/python-3106/), you will need a python module also called yt_dlp which you can install with the code below the installation of FFMPEG. You will need to go into the code and find the section where it says, "Specify the path to ffmpeg here" you will need to copy the code below the installation of yt_dlp and paste it into the terminal to get the file path to FFMPEG, once copied paste it into the section, "Specify the path to ffmpeg here" and enjoy!

```
brew install ffmpeg
```
```
pip install yt_dlp
```
```
which ffmpeg
```
# Features

- Uses FFMPEG to download the highest bitrate
- Can choose the preferred bit-rate
- Can download from Youtube or Youtube Music
- Can download single files or Playlists into one folder

NOTE: The section where it says to Enter File Name, you do not need to enter the file name since it doesn't work, because it automatically sets the name for you.

# Bugs and Suggestions

Feel free to make a Bug report and I will try my best to resolve the issue

Feel free to make any suggestions and I will take them into consideration

# Known Bugs

- None
