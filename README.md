# About

This script aims to simplify usage of [youtube-dl](https://github.com/rg3/youtube-dl) for regular downloads.

By now, it only supports setting for max height of video.

## How to use

The syntax is:

    $ ytdl URL [max Height]

### Example:

The following command will download best qualtiy of the video with ID of 11111111111 with maximum 360px height:

    $ ytdl https://www.youtube.com/watch?v=11111111111 360


## Installation

For user specific usage, copy the `ytdl` file into `~/bin/`. This directory will be added automatically into `$PATH` variable.

If you want to make it available for all users, copy `ytdl` to `/etc/`.
