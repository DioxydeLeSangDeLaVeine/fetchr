# Fetchr

Fetchr is a desktop app for downloading online videos and audio, **for free and with no limits**.

I made it because most apps and websites that offer this are paid or very limited (number of downloads, quality, length, ads…). Here there's none of that: paste a link, pick what you want, and it gets downloaded.

## Features

- Download video, audio only, or video only
- Pick the quality and format among everything available for the link
- Automatic merging of video and audio when they come separately, without re-encoding when possible
- Several downloads at the same time
- Pause and resume: closing the app, putting the computer to sleep or shutting it down pauses downloads instead of canceling them
- Detailed progress, speed and remaining time

## Download

Get the latest version from the [Releases](../../releases) tab.

- **Windows**: run the installer `Fetchr Setup x.x.x.exe`
- **Linux (Ubuntu / Debian)**: install the package with `sudo apt install ./Fetchr-x.x.x.deb`

## Usage

1. Copy the link of the video
2. Paste it into Fetchr and click **Analyze**
3. Choose the format and quality
4. Click **Download**, then choose where to save the file

Fetchr works with the sites supported by yt-dlp. It updates yt-dlp automatically at launch.

## Built with

Fetchr relies on these open-source projects, all credit goes to their authors:

| Project | Used for | License |
| --- | --- | --- |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Finding and downloading the videos and audio | Unlicense |
| [FFmpeg](https://ffmpeg.org) | Merging video and audio, converting formats | GPL (build by [BtbN](https://github.com/BtbN/FFmpeg-Builds)) |
| [Deno](https://deno.com) | JavaScript runtime needed by yt-dlp for some sites | MIT |
| [Electron](https://www.electronjs.org) | The desktop application framework | MIT |

## Something wrong?

If something doesn't work (a link that fails, a bug, an idea for an improvement), **don't hesitate to let me know** by opening an [issue](../../issues). Include the link concerned (if you can share it) and the error message shown, it will help me fix it faster.

## Good to know

Fetchr is a tool. Only download content you have the right to download: your own, content under a free license, or for personal use allowed by the law of your country and by the terms of the site concerned.
