# Twitch Leecher

If you are looking for a extremely fast and easy to use Twitch VOD downloader, this is your tool!

## What is different here compared to other VOD downloaders?

Nearly all of the well known VOD downloaders execute the download process via FFMPEG's integrated download capabilities. However, this is extremely slow. The download speed rarely exceeds 1.5Mbit even if the internet connection is 100 times faster. Twitch Leecher does not use FFMPEG for download tasks at all. It downloads thousands of small video chunks (usually ~500kb) in parallel while using all of the available bandwidth of your internet connection. As soon as all video chunks are downloaded, FFMPEG is only used to merge those chunks together in order to create a single video file again.

## Main Features

- Very easy to use, no manual needed
- Intuitive and stylish GUI
- Up to 20 times faster download speed compared to direct download with FFMPEG
- Browse your past broadcasts and highlights within the application
- Queue multiple downloads
- Free and Open Source
- Developed by an experienced Software Engineer

## Screenshot

![Twitch Leecher Screensht](http://www.fakesmilerevolution.com/files/fsr/twitchleecher/twitchleecher.jpg)

## LICENSE
[MIT License](https://github.com/Franiac/TwitchLeecher/blob/master/LICENSE)
