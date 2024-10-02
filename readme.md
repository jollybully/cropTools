# Crop Tools

This toolset allows you to crop and convert wide .mp4 video files into portrait or square formats, processing multiple files in bulk.

## How to Use

1. Drop your wide .mp4 video files into this folder.
2. Double-click either `wide-to-portrait` or `wide-to-square` to convert them to the desired format. These scripts will process all the videos in the folder.
3. The converted files will be placed in the `output` folder.

## Tools

- `wide-to-portrait`: Converts all .mp4 videos in the folder to a portrait (9:16) video.
- `wide-to-square`: Converts all .mp4 videos in the folder to a square (1:1) video.

## Running Unsigned Scripts on MacOS

If you're running these tools on MacOS, you might encounter security settings that prevent you from running unsigned scripts. Here's how to allow the script to run:

1. After attempting to run the script, go to **System Preferences**.
2. Click on **Security & Privacy**.
3. Select the **General** tab.
4. In the lower half of the window, you should see a message like "'wide-to-portrait' was blocked from use because it is not from an identified developer."
5. Click the button that says **Open Anyway** next to that message.
6. Confirm the action in the dialog that appears, and the script should run normally, processing all videos in the folder.

Note: The steps above will need to be repeated for each new script you want to run.

For more details about running unsigned scripts on MacOS, you can refer to Apple's official [support page](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac).

## Attribution

This toolset uses FFmpeg and FFprobe for video processing. The binaries for these tools are included in this repository for convenience.

- FFmpeg: A complete, cross-platform solution to record, convert and stream audio and video.
- FFprobe: A multimedia stream analyzer.

For more information about FFmpeg and FFprobe, visit [ffmpeg.org](https://ffmpeg.org/).

## Included Binaries

This repository includes macOS-specific binaries for FFmpeg and FFprobe. These binaries are pre-compiled and ready to use on macOS systems.

- `ffmpeg`: The FFmpeg binary for macOS
- `ffprobe`: The FFprobe binary for macOS

These binaries are included to ensure compatibility and ease of use on macOS systems. If you're using a different operating system, you may need to download the appropriate binaries for your system from the official FFmpeg website.

Note: The included binaries are specifically for macOS. If you're using a different operating system, please download the appropriate versions from the official FFmpeg website.
