MASHUP GENERATOR PROJECT

Author: Aadi Kant Sharma
Roll Number: 102303612


PROJECT OVERVIEW
This project creates a mashup by downloading songs of a given singer from YouTube, trimming a fixed duration from each song, merging them into one audio file, compressing it into a ZIP file, and sending it to an email address.


PROGRAM 1 – COMMAND LINE VERSION

File: 102303612.py

Description:
This program downloads N videos of a singer, converts them to audio, trims the first Y seconds from each, merges them, and creates a final mashup file.

Run Command:
py -3.11 102303612.py "<SingerName>" <NumberOfVideos> <DurationInSeconds> <OutputFileName>

Example:
py -3.11 102303612.py "Arijit Singh" 12 25 mashup.mp3

Output:
- mashup.mp3
- result.zip


PROGRAM 2 – EMAIL SERVICE

File: server.js

Description:
This program sends the generated ZIP file to an email using NodeMailer.

Setup:

1. Install Node.js
2. Run:
   npm init -y
   npm install nodemailer
3. Add your Gmail and App Password inside server.js

Run:

node server.js

Result:

The result.zip file is sent to the specified email.


TECHNOLOGIES USED

- Python
- yt-dlp
- moviepy
- pydub
- Node.js
- Nodemailer
- FFmpeg


NOTE
- Internet connection is required.
- Gmail App Password is required for sending email.
