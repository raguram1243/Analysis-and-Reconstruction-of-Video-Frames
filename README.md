# Analysis-and-Reconstruction-of-Video-Frames

Project Title: Analysis and Reconstruction of Video Frames
Objectives:
Extract Frame Information:
Analyze the frame rate, frame count, and duration of a sample video.
Frame Type Analysis:
Examine the distribution and compression efficiency of I, P, and B frames.
Frame Visualization:
Extract, display, and compare the visual quality of I, P, and B frames.
Advanced Frame Extraction:
Extract I frames and reconstruct a portion of the video using only these frames.
Requirements:
Python 3.x
ffmpeg
ffmpeg-python
matplotlib
opencv-python
PIL (Pillow)
Installation:
Install Python Packages:
bash
Copy code
pip install ffmpeg-python matplotlib opencv-python pillow
Install ffmpeg:
Download and install ffmpeg from ffmpeg.org and ensure it is added to your system's PATH.
Usage:
Extract Frame Information:

Use ffmpeg and ffmpeg-python to probe and analyze the video file for frame rate, frame count, and duration.
Frame Type Analysis:

Count the number of I, P, and B frames in the video and calculate their distribution.
Plot the distribution using matplotlib.
Frame Visualization:

Extract I, P, and B frames from the video using ffmpeg.
Display these frames using PIL or opencv-python.
Advanced Frame Extraction:

Extract I frames and save them as image files.
Reconstruct a video using the extracted I frames with a reduced frame rate.
