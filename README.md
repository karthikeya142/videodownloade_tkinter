# Video Downloader Application

This application allows users to download videos from YouTube using a simple graphical interface built with Tkinter.

## Features

- **Download Video**: Allows users to download videos from YouTube by providing the video URL.
- **Select Download Path**: Users can select the destination folder where the downloaded video will be saved.
- **User-Friendly Interface**: Built with Tkinter, providing a straightforward GUI for ease of use.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python (version 3.6 or higher)
- Required Python libraries:
  - tkinter: For creating the GUI.
  - pytube: For downloading videos from YouTube.
  - moviepy: For processing video files.
  
  You can install these libraries using pip:
  
  ```bash
  pip install tkinter pytube moviepy
  from tkinter import *
  from pytube import YouTube
  from moviepy.editor import *
  import shutil
 ```